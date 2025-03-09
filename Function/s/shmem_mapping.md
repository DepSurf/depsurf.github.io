# Function: <code>shmem_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580596576,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:1501",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580596576,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697264,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2158",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:show_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697264,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763056,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2176",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580763056,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580797760,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2232",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580797760,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887536,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2243",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887536,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023824,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2264",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:page_cache_tree_insert",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023824,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101584,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2226",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "fs/proc/task_mmu.c:smap_gather_stats",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101584,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165936,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2307",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "fs/proc/task_mmu.c:smap_gather_stats",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165936,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223856,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223856,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411440,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2308",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__uprobe_register",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smap_gather_stats",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411440,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581278966,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314995,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:page_cache_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381599,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443151,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_mmap",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733660,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581748965,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:find_get_incore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949122,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987508,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088049,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809111,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587486509,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581295190,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330549,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402506,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463951,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761787,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581776780,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:find_get_incore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581974826,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015281,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113121,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836951,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587368125,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:71",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581540105,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581464,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:page_cache_delete_batch",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655571,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:__invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719279,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_zero_setup",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044380,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582059700,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:find_get_incore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290752,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317969,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429441,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169591,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587935465,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:72",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581890344,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934657,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021314,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095542,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483821,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582497510,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:find_get_incore_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775051,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810026,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881163,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_pagecache_clean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945452,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660895,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589289089,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:73",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582323320,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362183,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455844,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479597,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:should_skip_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570618,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997720,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011946,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:filemap_get_incore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308902,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:hugepage_vma_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339421,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430763,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_pagecache_clean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583502375,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584268284,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590851139,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:79",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582524645,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567500,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660916,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_try_invalidate",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684118,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:should_skip_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777910,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_folio_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918403,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:folio_fast_pin_allowed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206322,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220163,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:filemap_get_incore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583528454,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:hugepage_vma_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583560931,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583652475,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_pagecache_clean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719431,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584498623,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591193769,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:81",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
  "name": "shmem_mapping",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582693573,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__uprobe_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738000,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_cachestat",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__filemap_remove_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582832100,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_try_invalidate",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854614,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:should_skip_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954232,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092529,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583441890,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455523,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:filemap_get_incore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722883,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page",
        "mm/huge_memory.c:__thp_vma_allowable_orders"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749395,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583846993,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:me_pagecache_clean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919912,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:__do_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584721423,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591540760,
      "name": "shmem_mapping",
      "external": false,
      "loc": "include/linux/shmem_fs.h:101",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492610080,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492610080,
      "name": "shmem_mapping",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226464336,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:__se_sys_memfd_create",
        "mm/memfd.c:memfd_fcntl",
        "mm/memfd.c:memfd_fcntl",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464336,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285929056,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285929056,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272639220,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639220,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581192704,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581192704,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139456,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139456,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581183904,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581183904,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool shmem_mapping(struct address_space * mapping)
```

```json
{
  "name": "shmem_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247152,
      "name": "shmem_mapping",
      "external": true,
      "loc": "mm/shmem.c:2327",
      "file": "mm/shmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:delete_from_page_cache_batch",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memfd.c:memfd_file_seals_ptr",
        "drivers/dma-buf/udmabuf.c:udmabuf_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247152,
      "name": "shmem_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
bool shmem_mapping(struct address_space * mapping)
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
