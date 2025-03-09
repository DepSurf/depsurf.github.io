# Function: <code>mem_cgroup_charge</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581982832,
      "name": "mem_cgroup_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6462",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982832,
      "name": "mem_cgroup_charge",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int mem_cgroup_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582033168,
      "name": "mem_cgroup_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6707",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582033168,
      "name": "mem_cgroup_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int mem_cgroup_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask)
```

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582056928,
      "name": "mem_cgroup_charge",
      "external": true,
      "loc": "mm/memcontrol.c:6559",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582056928,
      "name": "mem_cgroup_charge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581535267,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581711,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705442,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871801,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195537,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256903,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582272798,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311449,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412879,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:690",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581884081,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934834,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088032,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582267369,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658929,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744043,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582752722,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796600,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926286,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:684",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
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
  "name": "mem_cgroup_charge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317326,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362360,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560011,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759027,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182314,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275714,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583285538,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583334127,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482535,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:666",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518477,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565660,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582766393,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582974637,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399785,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492080,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583503634,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553695,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699249,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_charge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582687382,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736193,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964205,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_alloc_and_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152916,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639764,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683145,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702738,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743046,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583893696,
      "name": "mem_cgroup_charge",
      "external": false,
      "loc": "include/linux/memcontrol.h:685",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mem_cgroup_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int mem_cgroup_charge(struct page * page, struct mm_struct * mm, gfp_t gfp_mask)
```
</details>
</li>
</ul>
