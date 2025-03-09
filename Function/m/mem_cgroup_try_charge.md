# Function: <code>mem_cgroup_try_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942624,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5286",
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
      "addr": 18446744071580942624,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089488,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5364",
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
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
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
      "addr": 18446744071581089488,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581164480,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5349",
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
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
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
      "addr": 18446744071581164480,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212352,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5406",
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
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
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
      "addr": 18446744071581212352,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342704,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5489",
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
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
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
      "addr": 18446744071581342704,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490160,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5557",
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
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
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
      "addr": 18446744071581490160,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575936,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:5875",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_vma",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575936,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687200,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6167",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687200,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581760656,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581760656,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493214568,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_pte_range",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493214568,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226845556,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_mm",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226845556,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286726544,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_pte_range",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286726544,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272991014,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_pte_range",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272991014,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729392,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729392,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668160,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/swapfile.c:unuse_pte_range",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668160,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581720704,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581720704,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
```

```json
{
  "name": "mem_cgroup_try_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581788704,
      "name": "mem_cgroup_try_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6507",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_try_charge_delay",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581788704,
      "name": "mem_cgroup_try_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int mem_cgroup_try_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask, struct mem_cgroup * * memcgp, bool compound)
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
