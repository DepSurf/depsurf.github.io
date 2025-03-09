# Function: <code>hugetlb_vma_lock_write</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hugetlb_vma_lock_write(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583096125,
      "name": "hugetlb_vma_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:287",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range_final",
        "mm/hugetlb.c:__unmap_hugepage_range_final",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074752,
      "name": "hugetlb_vma_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void hugetlb_vma_lock_write(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583306007,
      "name": "hugetlb_vma_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:281",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range_final",
        "mm/hugetlb.c:__unmap_hugepage_range_final",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285296,
      "name": "hugetlb_vma_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void hugetlb_vma_lock_write(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_lock_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524672,
      "name": "hugetlb_vma_lock_write",
      "external": true,
      "loc": "mm/hugetlb.c:291",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__hugetlb_zap_begin",
        "mm/hugetlb.c:move_hugetlb_page_tables"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524672,
      "name": "hugetlb_vma_lock_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void hugetlb_vma_lock_write(struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
