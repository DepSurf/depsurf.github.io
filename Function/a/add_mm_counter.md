# Function: <code>add_mm_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580662854,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1370",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:sync_mm_rss",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898910,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1370",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020120,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1370",
      "file": "fs/exec.c",
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580787502,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872109,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032475,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050320,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180480,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "fs/exec.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580851798,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1438",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939996,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1438",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107683,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1438",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133271,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1438",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257623,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1438",
      "file": "fs/exec.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580897103,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1470",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984529,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1470",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146398,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1470",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173356,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1470",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306681,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1470",
      "file": "fs/exec.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995642,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1544",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087569,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1544",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280654,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1544",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309757,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1544",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446349,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1544",
      "file": "fs/exec.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581129731,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1631",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230424,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1631",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429203,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1631",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451442,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1631",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605556,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1631",
      "file": "fs/exec.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209497,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1701",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313403,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1701",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501062,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1701",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535060,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1701",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690979,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1701",
      "file": "fs/exec.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581284448,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1696",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423958,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1696",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610692,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1696",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638280,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1696",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581808950,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1696",
      "file": "fs/exec.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581343168,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485350,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681604,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720550,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881542,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581517914,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1882",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690581,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1882",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900183,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1882",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940037,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1882",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104542,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1882",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581563655,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1927",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740325,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1927",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945719,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1927",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987168,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1927",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149918,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1927",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581604026,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1935",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768606,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1935",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971677,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1935",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582014933,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1935",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174654,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1935",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581870244,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1964",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051262,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1964",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274326,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1964",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317635,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1964",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491998,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1964",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void add_mm_counter(struct mm_struct * mm, int member, long int value)
```

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265480,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476870,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757301,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582790384,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583015598,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2042",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790384,
      "name": "add_mm_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void add_mm_counter(struct mm_struct * mm, int member, long int value)
```

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582756915,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2208",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991132,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2208",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291271,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2208",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324704,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2208",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583581969,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2208",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324704,
      "name": "add_mm_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void add_mm_counter(struct mm_struct * mm, int member, long int value)
```

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582972729,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202232,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510061,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543424,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583798001,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2528",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543424,
      "name": "add_mm_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void add_mm_counter(struct mm_struct * mm, int member, long int value)
```

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583150933,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2577",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437773,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2577",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700368,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2577",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583762644,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2577",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071584004833,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:2577",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737088,
      "name": "add_mm_counter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492748096,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903808,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129128,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493168052,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493352524,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226570800,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 3226695916,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226940960,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:acct_arg_size"
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286107008,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286305116,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286603960,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286662332,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286902732,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272735226,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272828074,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273083626,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:copy_strings"
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
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312016,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454198,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650340,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689286,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850278,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581255733,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396128,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589101,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628316,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787942,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581303216,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445398,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641652,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680598,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841590,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_mm_counter",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581367194,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509877,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708036,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747362,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911145,
      "name": "add_mm_counter",
      "external": false,
      "loc": "include/linux/mm.h:1668",
      "file": "fs/exec.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void add_mm_counter(struct mm_struct * mm, int member, long int value)
```
</details>
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
