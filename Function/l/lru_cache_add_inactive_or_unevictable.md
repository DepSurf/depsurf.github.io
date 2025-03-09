# Function: <code>lru_cache_add_inactive_or_unevictable</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379056,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/swap.c:478",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379056,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400016,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/swap.c:488",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400016,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650576,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/swap.c:466",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650576,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017552,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/swap.c:480",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017552,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431552,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/folio-compat.c:79",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431552,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```

```json
{
  "name": "lru_cache_add_inactive_or_unevictable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636928,
      "name": "lru_cache_add_inactive_or_unevictable",
      "external": true,
      "loc": "mm/folio-compat.c:80",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636928,
      "name": "lru_cache_add_inactive_or_unevictable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void lru_cache_add_inactive_or_unevictable(struct page * page, struct vm_area_struct * vma)
```
</details>
</li>
</ul>
