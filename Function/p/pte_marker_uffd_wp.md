# Function: <code>pte_marker_uffd_wp</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool pte_marker_uffd_wp(pte_t pte)
```

```json
{
  "name": "pte_marker_uffd_wp",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265859,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:290",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374310,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:290",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583825,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:290",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    },
    {
      "addr": 18446744071583667675,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:290",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554240,
      "name": "pte_marker_uffd_wp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_marker_uffd_wp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582757206,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:289",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582877720,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:289",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115039,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:289",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584278659,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:289",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range"
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
  "name": "pte_marker_uffd_wp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582973584,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:325",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092817,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:325",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325476,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:325",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559672,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:325",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584508729,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:325",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range"
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
  "name": "pte_marker_uffd_wp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583151147,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:366",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275039,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:366",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561564,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:366",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583759568,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:366",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584731922,
      "name": "pte_marker_uffd_wp",
      "external": false,
      "loc": "include/linux/userfaultfd_k.h:366",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool pte_marker_uffd_wp(pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool pte_marker_uffd_wp(pte_t pte)
```
</details>
</li>
</ul>
