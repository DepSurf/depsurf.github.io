# Function: <code>maybe_pmd_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899295,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:699",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900000,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036539,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:445",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024720,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581111723,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:475",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099536,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581160277,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:477",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148336,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293806,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:477",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268848,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581440836,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:477",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417680,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524257,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:487",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503744,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581633379,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:492",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613488,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581704419,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684400,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581920450,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902672,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581967122,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:477",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948848,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581995233,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:494",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974416,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582297425,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:494",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277088,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582785517,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:493",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760928,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583318717,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:554",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294816,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583526789,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:551",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513920,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583721077,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:762",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707712,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493140600,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493131728,
      "name": "maybe_pmd_mkwrite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286637920,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286610736,
      "name": "maybe_pmd_mkwrite",
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581673155,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653136,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581612610,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593360,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581664467,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644448,
      "name": "maybe_pmd_mkwrite",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_pmd_mkwrite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581730835,
      "name": "maybe_pmd_mkwrite",
      "external": true,
      "loc": "mm/huge_memory.c:484",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:alloc_set_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710864,
      "name": "maybe_pmd_mkwrite",
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
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
pmd_t maybe_pmd_mkwrite(pmd_t pmd, struct vm_area_struct * vma)
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
