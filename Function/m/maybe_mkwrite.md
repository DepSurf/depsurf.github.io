# Function: <code>maybe_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:572",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580880540,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:572",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:572",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580788188,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008170,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:621",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033388,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:621",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580852472,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:608",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082194,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:608",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108576,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:608",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897432,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:664",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130908,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:664",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147096,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:664",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995959,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:681",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244930,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:681",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281625,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:681",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581130059,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:723",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390086,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:723",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430204,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:723",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209101,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:751",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473782,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:751",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501955,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:751",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581283587,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:817",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589159,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:817",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611593,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:817",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581342307,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652823,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682505,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581539515,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:943",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870849,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:943",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901039,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:943",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581582722,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:984",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917133,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:984",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946565,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:984",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581604314,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1007",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_reuse",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942104,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1007",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972494,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1007",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581870506,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1011",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247837,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1011",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275144,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1011",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582265924,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:978",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719299,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:978",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758435,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:978",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582757376,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1108",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246419,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1108",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583292366,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1108",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
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
  "name": "maybe_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582973170,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1294",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
pte_t maybe_mkwrite(pte_t pte, struct vm_area_struct * vma)
```

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583151268,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:1348",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122736,
      "name": "maybe_mkwrite",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492748480,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493101392,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129464,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226579816,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226802112,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286105844,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286560288,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286604704,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272732036,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272950086,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311155,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621559,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651241,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254755,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562865,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589812,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581302355,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612871,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642553,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
  "name": "maybe_mkwrite",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581366335,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680471,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708937,
      "name": "maybe_mkwrite",
      "external": false,
      "loc": "include/linux/mm.h:830",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
pte_t maybe_mkwrite(pte_t pte, struct vm_area_struct * vma)
```
</details>
</li>
</ul>
