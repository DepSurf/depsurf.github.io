# Function: <code>vma_alloc_folio</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, bool hugepage)
```

```json
{
  "name": "vma_alloc_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vma_alloc_folio",
      "external": true,
      "loc": "mm/mempolicy.c:2153",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593994530,
      "name": "vma_alloc_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071582615248,
      "name": "vma_alloc_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 927
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, bool hugepage)
```

```json
{
  "name": "vma_alloc_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vma_alloc_folio",
      "external": true,
      "loc": "mm/mempolicy.c:2168",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044727,
      "name": "vma_alloc_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583139072,
      "name": "vma_alloc_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct folio * vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, bool hugepage)
```

```json
{
  "name": "vma_alloc_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vma_alloc_folio",
      "external": true,
      "loc": "mm/mempolicy.c:2179",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_folio",
        "mm/shmem.c:shmem_alloc_hugefolio",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_folio",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596567161,
      "name": "vma_alloc_folio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071583349328,
      "name": "vma_alloc_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct folio * vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, bool hugepage)
```

```json
{
  "name": "vma_alloc_folio",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583587552,
      "name": "vma_alloc_folio",
      "external": true,
      "loc": "mm/mempolicy.c:2164",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_anon_folio",
        "mm/memory.c:alloc_anon_folio",
        "mm/memory.c:alloc_anon_folio",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583587552,
      "name": "vma_alloc_folio",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct folio * vma_alloc_folio(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, bool hugepage)
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
