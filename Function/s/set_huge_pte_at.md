# Function: <code>set_huge_pte_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_huge_pte_at",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580802416,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:37",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault"
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
  "name": "set_huge_pte_at",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580927290,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:38",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
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
  "name": "set_huge_pte_at",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995626,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:38",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:38",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581044524,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:38",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130651,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:38",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581155010,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244658,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581201287,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298473,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390143,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "arch/x86/include/asm/hugetlb.h:39",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581285015,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382047,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473839,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581359297,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493339,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588782,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581418975,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557834,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652446,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581620408,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768173,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870474,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581666578,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816421,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916600,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581688676,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844416,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941607,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581960204,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582135697,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247320,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582377649,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582584950,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718644,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582881173,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583114706,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245659,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:71",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583095949,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583325093,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465309,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583278118,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583561195,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660489,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730983,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:78",
      "file": "fs/proc/task_mmu.c",
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
void set_huge_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "set_huge_pte_at",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490355400,
      "name": "set_huge_pte_at",
      "external": true,
      "loc": "arch/arm64/mm/hugetlbpage.c:173",
      "file": "arch/arm64/mm/hugetlbpage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490355400,
      "name": "set_huge_pte_at",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282813168,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "arch/powerpc/mm/book3s64/hash_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_hugetlbpage.c:huge_ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282815116,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "arch/powerpc/mm/book3s64/radix_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286201412,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286423160,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286559568,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272895712,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272949726,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581387823,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526570,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621182,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581330560,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468679,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562527,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581379023,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517882,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612494,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
  "name": "set_huge_pte_at",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581442889,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582872,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680094,
      "name": "set_huge_pte_at",
      "external": false,
      "loc": "include/asm-generic/hugetlb.h:53",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
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
void set_huge_pte_at(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
</ul>
