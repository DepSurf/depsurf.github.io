# Function: <code>mem_cgroup_cancel_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943056,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5400",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943056,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089920,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5471",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089920,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164928,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5456",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164928,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212720,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5513",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212720,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343088,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5596",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343088,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490560,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5664",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_vma",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490560,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576416,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5995",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_vma",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576416,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687680,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6287",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687680,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761136,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761136,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mem_cgroup_cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583793386,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2938",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc"
      ],
      "caller_func": [
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817824,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493215080,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493215080,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226846144,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226846144,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286727456,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286727456,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272991522,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272991522,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729872,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729872,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668640,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668640,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721184,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721184,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```

```json
{
  "name": "mem_cgroup_cancel_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789264,
      "name": "mem_cgroup_cancel_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6627",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789264,
      "name": "mem_cgroup_cancel_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool compound</code>
</li>
</ul>
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void mem_cgroup_cancel_charge(struct page * page, struct mem_cgroup * memcg, bool compound)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_cancel_charge(struct mem_cgroup * memcg, unsigned int nr_pages)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
