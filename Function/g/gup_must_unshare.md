# Function: <code>gup_must_unshare</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gup_must_unshare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582230468,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3054",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582594637,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3054",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763945,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3054",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_trans_huge_pmd"
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
  "name": "gup_must_unshare",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582720686,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3208",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583112638,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3208",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297956,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "include/linux/mm.h:3208",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_trans_huge_pmd"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool gup_must_unshare(struct vm_area_struct * vma, unsigned int flags, struct page * page)
```

```json
{
  "name": "gup_must_unshare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582923248,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:969",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071583323145,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:969",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517035,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:969",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923248,
      "name": "gup_must_unshare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
bool gup_must_unshare(struct vm_area_struct * vma, unsigned int flags, struct page * page)
```

```json
{
  "name": "gup_must_unshare",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583097456,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:1059",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_huge_pud",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte"
      ]
    },
    {
      "addr": 18446744071583544987,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:1059",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711214,
      "name": "gup_must_unshare",
      "external": false,
      "loc": "mm/internal.h:1059",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097456,
      "name": "gup_must_unshare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool gup_must_unshare(struct vm_area_struct * vma, unsigned int flags, struct page * page)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
