# Function: <code>folio_mapped</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool folio_mapped(struct folio * folio)
```

```json
{
  "name": "folio_mapped",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582112208,
      "name": "folio_mapped",
      "external": true,
      "loc": "mm/util.c:754",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_unaccount_folio",
        "mm/folio-compat.c:page_mapped",
        "mm/folio-compat.c:page_mapped",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_folio",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/rmap.c:page_not_mapped",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112208,
      "name": "folio_mapped",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
  "name": "folio_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317800,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357669,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449709,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455648,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519676,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:isolate_folio",
        "mm/vmscan.c:isolate_folio",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582578484,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866629,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980615,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583010917,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033223,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166717,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254647,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269062,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583341025,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583391322,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489939,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584587025,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585098507,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585247231,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:936",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
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
  "name": "folio_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518913,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582560757,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582654893,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660720,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721326,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774647,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583084021,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583193030,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583219253,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241936,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382911,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583473865,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489430,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562384,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616803,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657022,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583705141,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584815265,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585328072,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585476975,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1181",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
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
  "name": "folio_mapped",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582687803,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731541,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_unaccount_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826026,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:perf_trace_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion",
        "mm/swap.c:trace_event_raw_event_mm_lru_insertion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582831577,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_cleanup_folio",
        "mm/truncate.c:truncate_cleanup_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890711,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:isolate_lru_folios",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950833,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266133,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_not_mapped",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:folio_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583377329,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454613,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476416,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622409,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666329,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688550,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750541,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811680,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853084,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905493,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585048845,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_release_unused_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585562769,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585711990,
      "name": "folio_mapped",
      "external": false,
      "loc": "include/linux/mm.h:1264",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool folio_mapped(struct folio * folio)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool folio_mapped(struct folio * folio)
```
</details>
</li>
</ul>
