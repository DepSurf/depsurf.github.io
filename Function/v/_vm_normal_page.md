# Function: <code>_vm_normal_page</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct page * _vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, bool with_public_device)
```

```json
{
  "name": "_vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983808,
      "name": "_vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:822",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983808,
      "name": "_vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct page * _vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, bool with_public_device)
```

```json
{
  "name": "_vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581118496,
      "name": "_vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:829",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581118496,
      "name": "_vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page * _vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, bool with_public_device)
```

```json
{
  "name": "_vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197280,
      "name": "_vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:572",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197280,
      "name": "_vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct page * _vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, bool with_public_device)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct page * _vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte, bool with_public_device)
```
</details>
</li>
</ul>
