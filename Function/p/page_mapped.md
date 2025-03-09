# Function: <code>page_mapped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580448954,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580476683,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534167,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543476,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_page",
        "mm/truncate.c:invalidate_inode_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559017,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583309,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722213,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:try_to_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756373,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766736,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:free_swap_and_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830673,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886720,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920357,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949459,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975893,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499555,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940136,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050852,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:982",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580699056,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:354",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "fs/proc/page.c:stable_page_flags",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699056,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764864,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:357",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764864,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580801248,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:441",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801248,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580889952,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:441",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889952,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581025680,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:467",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025680,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581103200,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:470",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_copy_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103200,
      "name": "page_mapped",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581168096,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:513",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168096,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581226064,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226064,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581413280,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:646",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mc_handle_present_pte",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413280,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581455936,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:659",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page_prepare",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455936,
      "name": "page_mapped",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581476800,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:659",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581476800,
      "name": "page_mapped",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581731120,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:680",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731120,
      "name": "page_mapped",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994256,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/folio-compat.c:42",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:isolate_lru_pages",
        "mm/shmem.c:shmem_writepage",
        "mm/memory.c:__do_fault",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "fs/proc/page.c:stable_page_flags",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994256,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "page_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582754488,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583167366,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_stable_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269087,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380019,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441023,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383079,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:948",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags"
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
  "name": "page_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582969976,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583383334,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_stable_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489455,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600271,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663314,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611387,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1193",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags"
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
  "name": "page_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583149952,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623142,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:remove_stable_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688572,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797654,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857337,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:hwpoison_user_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584843324,
      "name": "page_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1276",
      "file": "fs/proc/page.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/page.c:stable_page_flags"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492614576,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492614576,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226465940,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226465940,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285932416,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285932416,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272641150,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272641150,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581194912,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194912,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581141664,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141664,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581186112,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186112,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool page_mapped(struct page * page)
```

```json
{
  "name": "page_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581249360,
      "name": "page_mapped",
      "external": true,
      "loc": "mm/util.c:618",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_page",
        "mm/truncate.c:truncate_cleanup_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_writepage",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_get_anon_vma",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:remove_stable_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/proc/page.c:stable_page_flags",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249360,
      "name": "page_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool page_mapped(struct page * page)
```
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool page_mapped(struct page * page)
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
