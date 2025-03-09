# Function: <code>hugetlb_vma_unlock_read</code>

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
void hugetlb_vma_unlock_read(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_unlock_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583110840,
      "name": "hugetlb_vma_unlock_read",
      "external": true,
      "loc": "mm/hugetlb.c:278",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074672,
      "name": "hugetlb_vma_unlock_read",
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
void hugetlb_vma_unlock_read(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_unlock_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583322030,
      "name": "hugetlb_vma_unlock_read",
      "external": true,
      "loc": "mm/hugetlb.c:272",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285216,
      "name": "hugetlb_vma_unlock_read",
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
void hugetlb_vma_unlock_read(struct vm_area_struct * vma)
```

```json
{
  "name": "hugetlb_vma_unlock_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583524576,
      "name": "hugetlb_vma_unlock_read",
      "external": true,
      "loc": "mm/hugetlb.c:278",
      "file": "mm/hugetlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/pagewalk.c:__walk_page_range",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_handle_userfault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "fs/userfaultfd.c:handle_userfault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524576,
      "name": "hugetlb_vma_unlock_read",
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
void hugetlb_vma_unlock_read(struct vm_area_struct * vma)
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
