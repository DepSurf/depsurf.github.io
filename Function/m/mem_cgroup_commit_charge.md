# Function: <code>mem_cgroup_commit_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580943664,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5352",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580943664,
      "name": "mem_cgroup_commit_charge",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581091552,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5427",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581091552,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1253
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166768,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5412",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166768,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1283
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214544,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5469",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214544,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1318
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581345168,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5552",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345168,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1318
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493072,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5620",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_unuse",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493072,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1318
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581578944,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5951",
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
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581578944,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1225
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690064,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6243",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690064,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581763488,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581763488,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_commit_charge(struct folio * folio, struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583817936,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:2968",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583817936,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493217440,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493217440,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1092
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226848660,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226848660,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286731184,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286731184,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1480
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272993632,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272993632,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581732224,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581732224,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670880,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670880,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581723536,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581723536,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1157
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```

```json
{
  "name": "mem_cgroup_commit_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791760,
      "name": "mem_cgroup_commit_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6583",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791760,
      "name": "mem_cgroup_commit_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1148
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
void mem_cgroup_commit_charge(struct page * page, struct mem_cgroup * memcg, bool lrucare, bool compound)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void mem_cgroup_commit_charge(struct folio * folio, struct mem_cgroup * memcg)
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
