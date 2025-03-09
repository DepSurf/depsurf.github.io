# Function: <code>native_set_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579256416,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pmd_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256416,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579255537,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pmd_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255472,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269057,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:63",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pmd_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268992,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
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
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265665,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:72",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/paravirt.c:native_set_pmd_at"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265600,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579282432,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602724129,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__sme_map_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995676,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581264332,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293764,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310194,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:74",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282432,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579293888,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602897797,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129765,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195349,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411330,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440904,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451862,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959865,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094353,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293888,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318880,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604695189,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318880,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334080,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604795217,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334080,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579338288,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604820949,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338288,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367984,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609159237,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367984,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579367008,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612229835,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367008,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371360,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614370581,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371360,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579432576,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615302559,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432576,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579501568,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617082841,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501568,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598704,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627738264,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598704,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579611424,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619497384,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611424,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641200,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621794216,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:81",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641200,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334192,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604734829,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334192,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581917,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009827,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579234744,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589493583,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:cleanup_highmap",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604691166,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306472,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:populate_pmd",
        "arch/x86/mm/pageattr.c:alloc_pte_page",
        "arch/x86/mm/pageattr.c:unmap_pmd_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327603,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page",
        "arch/x86/mm/pgtable.c:pmd_clear_huge",
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339728,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355263,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702450,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255168,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:__pte_alloc_kernel",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313041,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323827,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324679,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400191,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504405,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pmd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582977,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612490,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625125,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189383,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360213,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587642905,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648589,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579334112,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604812396,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334112,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```

```json
{
  "name": "native_set_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579342464,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604825106,
      "name": "native_set_pmd",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable_64.h:75",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range",
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342464,
      "name": "native_set_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void native_set_pmd(pmd_t * pmdp, pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
