# Function: <code>swp_entry_to_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580685592,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715424,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580726144,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762244,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580806059,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580799028,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830838,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580845835,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884673,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927538,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033164,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580863270,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896413,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580916156,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952753,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995870,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108349,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580908211,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941291,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960142,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998114,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044618,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146880,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580985581,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041293,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062539,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109138,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155131,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251449,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281389,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581120653,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581176847,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201729,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245795,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298473,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393984,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429943,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:80",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581199445,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581260571,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581285447,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329315,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382047,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479630,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501702,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581272170,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581334029,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359722,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439849,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581493339,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589260,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611335,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581330970,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581393437,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419415,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504073,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581557834,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657645,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682247,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581527698,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_one_pte",
        "mm/memory.c:copy_one_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591905,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620976,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711370,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768173,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876580,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900769,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581562447,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581637911,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667179,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759162,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816421,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925785,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946302,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:81",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581588457,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581659554,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689139,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786111,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844416,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948022,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972229,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581854800,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927786,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961120,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069887,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135647,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252607,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274924,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:88",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582249447,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582335319,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380412,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509254,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584920,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719121,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741463,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758283,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:90",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582737713,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836500,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883892,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027962,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115589,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246140,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272763,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291774,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582964795,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583051594,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098723,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250693,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326063,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465194,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496059,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510601,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t swp_entry_to_pte(swp_entry_t entry)
```

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583142663,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": [
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583233300,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281002,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485173,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562096,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661021,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684128,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700913,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583899739,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_poison"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730456,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:146",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:make_uffd_wp_pte"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127216,
      "name": "swp_entry_to_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492738752,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492799024,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818612,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492933292,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492997620,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493129896,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226569168,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612772,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226625920,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3226720504,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286088908,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286171316,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286201932,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286343124,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286423160,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286574368,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286605388,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272736632,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765550,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272777106,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272851990,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272895712,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581299818,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581362285,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388263,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472809,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581526570,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626381,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650983,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581245113,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306502,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330979,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421475,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468637,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567562,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589619,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581291018,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581353485,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379463,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464121,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517882,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617693,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642295,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "swp_entry_to_pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581355200,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581417419,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443312,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528844,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581582872,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686137,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708679,
      "name": "swp_entry_to_pte",
      "external": false,
      "loc": "include/linux/swapops.h:79",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
pte_t swp_entry_to_pte(swp_entry_t entry)
```
</details>
</li>
</ul>
