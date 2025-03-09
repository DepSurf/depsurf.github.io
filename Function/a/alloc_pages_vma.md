# Function: <code>alloc_pages_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819424,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:1959",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819424,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580944848,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:1976",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580944848,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581017056,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:1970",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581017056,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 589
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063024,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:1891",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063024,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174112,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:1953",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174112,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318800,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2010",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318800,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581402960,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2050",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402960,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581514048,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2095",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514048,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578416,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578416,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581790144,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2194",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581790144,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581837888,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2169",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581837888,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581868704,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2175",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868704,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2085",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592215833,
      "name": "alloc_pages_vma.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071582159792,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 886
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493015984,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493015984,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286442704,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286442704,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547152,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547152,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581488800,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581488800,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581538464,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538464,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```

```json
{
  "name": "alloc_pages_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581603504,
      "name": "alloc_pages_vma",
      "external": true,
      "loc": "mm/mempolicy.c:2098",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/shmem.c:shmem_alloc_page",
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603504,
      "name": "alloc_pages_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool hugepage</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool hugepage</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct page * alloc_pages_vma(gfp_t gfp, int order, struct vm_area_struct * vma, long unsigned int addr, int node, bool hugepage)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
