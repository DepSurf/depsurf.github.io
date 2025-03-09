# Function: <code>pmd_same</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307917,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:267",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889964,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:267",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901485,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:267",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
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
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307718,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:272",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020486,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:272",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028771,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:272",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579322950,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:296",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095090,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:296",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104047,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:296",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579320214,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:371",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141904,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153679,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579343302,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:372",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264150,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:372",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274784,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:372",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579354517,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:379",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411112,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:379",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423476,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:379",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346850,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579381637,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494535,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509332,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346850,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362553,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579397109,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602456,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618932,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362553,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579366793,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579400421,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673144,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689780,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366793,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591183664,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:537",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409669,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:537",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891672,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:537",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913067,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:537",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591679017,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410313,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937720,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958749,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591622711,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413481,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963207,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984734,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:592",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592796038,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:611",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476361,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:611",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286720,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:611",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594695978,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:644",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554441,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:644",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764831,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:644",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596434089,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:680",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579661140,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:680",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298928,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:680",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596974839,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:692",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579675300,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:692",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079111,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:692",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522679,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:692",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597903271,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:820",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709428,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:820",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261415,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:820",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713643,
      "name": "pmd_same",
      "external": false,
      "loc": "include/linux/pgtable.h:820",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282755908,
      "name": "pmd_same",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1222",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286594200,
      "name": "pmd_same",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1222",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286617380,
      "name": "pmd_same",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1222",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362697,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579396325,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641880,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658516,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362697,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579362617,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579396245,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633192,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649828,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579362617,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```

```json
{
  "name": "pmd_same",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371049,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579404741,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_set_access_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699528,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716260,
      "name": "pmd_same",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:378",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:huge_pmd_set_accessed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371049,
      "name": "pmd_same",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
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
int pmd_same(pmd_t pmd_a, pmd_t pmd_b)
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
