# Function: <code>folio_mapping</code>

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
struct address_space * folio_mapping(struct folio * folio)
```

```json
{
  "name": "folio_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582111024,
      "name": "folio_mapping",
      "external": true,
      "loc": "mm/util.c:795",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_mark_dirty",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_undo_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:folio_mkclean",
        "mm/migrate.c:move_to_new_folio",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111024,
      "name": "folio_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * folio_mapping(struct folio * folio)
```

```json
{
  "name": "folio_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582585312,
      "name": "folio_mapping",
      "external": true,
      "loc": "mm/util.c:741",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_mark_dirty",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/swap.c:lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_undo_range",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:folio_mkclean",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_folio",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585312,
      "name": "folio_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * folio_mapping(struct folio * folio)
```

```json
{
  "name": "folio_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792608,
      "name": "folio_mapping",
      "external": true,
      "loc": "mm/util.c:764",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_mark_dirty",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/swap.c:lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:folio_mkclean",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_folio",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792608,
      "name": "folio_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * folio_mapping(struct folio * folio)
```

```json
{
  "name": "folio_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582967632,
      "name": "folio_mapping",
      "external": true,
      "loc": "mm/util.c:771",
      "file": "mm/util.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_release_folio",
        "mm/page-writeback.c:folio_wait_stable",
        "mm/page-writeback.c:folio_wait_writeback_killable",
        "mm/page-writeback.c:folio_wait_writeback",
        "mm/page-writeback.c:__folio_start_writeback",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/page-writeback.c:folio_clear_dirty_for_io",
        "mm/page-writeback.c:__folio_cancel_dirty",
        "mm/page-writeback.c:folio_mark_dirty",
        "mm/folio-compat.c:__set_page_dirty_nobuffers",
        "mm/swap.c:lru_add_fn",
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:sort_folio",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_folios_to_lru",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:folio_mkclean",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_folio",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_clean",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967632,
      "name": "folio_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct address_space * folio_mapping(struct folio * folio)
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
