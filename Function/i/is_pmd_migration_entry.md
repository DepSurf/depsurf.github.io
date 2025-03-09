# Function: <code>is_pmd_migration_entry</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580968576,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001632,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051332,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168267,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257350,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280968,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581103585,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189827,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312965,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403526,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429462,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581183365,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272800,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394501,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487014,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514801,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627876,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:286",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581253560,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347264,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506693,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595158,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624415,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746964,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312161,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406576,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571061,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665718,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695288,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819198,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581501830,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605413,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788861,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581887222,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913262,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036831,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541990,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652559,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836285,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581933126,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958930,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085663,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:273",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int is_pmd_migration_entry(pmd_t pmd)
```

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581565190,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581614771,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673541,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867101,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581958518,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971338,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    },
    {
      "addr": 18446744071582111000,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:282",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967504,
      "name": "is_pmd_migration_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
int is_pmd_migration_entry(pmd_t pmd)
```

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581829956,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581882128,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942890,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158144,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582263254,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273978,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    },
    {
      "addr": 18446744071582427320,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:305",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582270192,
      "name": "is_pmd_migration_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582284388,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352474,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613398,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582731559,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770547,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943932,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:425",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582776858,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853773,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137042,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583252183,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305189,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500869,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:520",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582993109,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070157,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078291,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583347426,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583471655,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524481,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715257,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:511",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int is_pmd_migration_entry(pmd_t pmd)
```

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583174950,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252059,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260630,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583435,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663959,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719233,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    },
    {
      "addr": 18446744071583916152,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:516",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583698240,
      "name": "is_pmd_migration_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/hmm.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/hmm.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286062576,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286111332,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183928,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286436120,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286583128,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286624144,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286818024,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:300",
      "file": "mm/hmm.c",
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581281009,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375424,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539797,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634454,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664024,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787934,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581227163,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318764,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481548,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575462,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603763,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725836,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272209,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366624,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531109,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625766,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655336,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779246,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
  "name": "is_pmd_migration_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581336090,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430518,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593718,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692120,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721725,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848206,
      "name": "is_pmd_migration_entry",
      "external": false,
      "loc": "include/linux/swapops.h:271",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int is_pmd_migration_entry(pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int is_pmd_migration_entry(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int is_pmd_migration_entry(pmd_t pmd)
```
</details>
</li>
</ul>
