# Function: <code>arch_hugetlb_migration_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581412818,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478522,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596062,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581473842,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542810,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666622,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581679655,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:650",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757789,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:650",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787976,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:650",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884033,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:650",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
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
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581727420,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:648",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792896,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:648",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:allowed_mems_nr",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835400,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:648",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930054,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:648",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
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
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749788,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:750",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581832762,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:750",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866216,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:750",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939565,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:750",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page"
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
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582029673,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:773",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122205,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:773",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157240,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:773",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582244047,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:773",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page"
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
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582568461,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:803",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612476,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:803",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582717885,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:803",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582899534,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:803",
      "file": "mm/page_isolation.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627878770,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:dequeue_huge_page_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135753,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:855",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583247139,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:855",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451634,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:855",
      "file": "mm/page_isolation.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619641938,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:883",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio_vma",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346076,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:883",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462542,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:883",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671538,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:883",
      "file": "mm/page_isolation.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583539833,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:905",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_hstate_alloc_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio",
        "mm/hugetlb.c:gather_surplus_pages",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:dequeue_hugetlb_folio_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582172,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:905",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:vma_migratable",
        "mm/mempolicy.c:alloc_migration_target_by_mpol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655448,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:905",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:alloc_migration_target",
        "mm/migrate.c:migrate_hugetlbs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583866072,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:905",
      "file": "mm/page_isolation.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool arch_hugetlb_migration_supported(struct hstate * h)
```

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490355152,
      "name": "arch_hugetlb_migration_supported",
      "external": true,
      "loc": "arch/arm64/mm/hugetlbpage.c:23",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:has_unmovable_pages",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490355152,
      "name": "arch_hugetlb_migration_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286281360,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286394520,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286584624,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:498",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:498",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:498",
      "file": "mm/migrate.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581442690,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511546,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581635358,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581385074,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453738,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576318,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581433890,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502858,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626670,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_hugetlb_migration_supported",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498386,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:has_unmovable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567793,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page",
        "mm/hugetlb.c:alloc_huge_page_vma",
        "mm/hugetlb.c:alloc_huge_page_nodemask",
        "mm/hugetlb.c:alloc_huge_page_node",
        "mm/hugetlb.c:alloc_pool_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692990,
      "name": "arch_hugetlb_migration_supported",
      "external": false,
      "loc": "include/linux/hugetlb.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
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

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
bool arch_hugetlb_migration_supported(struct hstate * h)
```
</details>
</li>
</ul>
