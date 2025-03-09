# Function: <code>page_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580598496,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:331",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "mm/page-writeback.c:__set_page_dirty_nobuffers",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_replace_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/buffer.c:mark_buffer_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580598496,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698592,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:384",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698592,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764368,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:387",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764368,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800592,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:471",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800592,
      "name": "page_mapping",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889296,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:471",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889296,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024528,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:497",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024528,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102048,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:500",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:expected_page_refs",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102048,
      "name": "page_mapping",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166992,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:543",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166992,
      "name": "page_mapping",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224784,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224784,
      "name": "page_mapping",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581412352,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:676",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:page_check_dirty_writeback",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581412352,
      "name": "page_mapping",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455024,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:689",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:__isolate_lru_page_prepare",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:page_check_dirty_writeback",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/mlock.c:__putback_lru_fast_prepare",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455024,
      "name": "page_mapping",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475904,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:689",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:wait_on_page_writeback_killable",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475904,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729968,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:710",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:wait_on_page_writeback_killable",
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/swap.c:__pagevec_lru_add_fn",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/crypto/inline_crypt.c:fscrypt_mergeable_bio_bh",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729968,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581995099,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/folio-compat.c:12",
      "file": "mm/folio-compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:__set_page_dirty_nobuffers"
      ],
      "caller_func": [
        "mm/filemap.c:page_endio",
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_pages_to_lru",
        "mm/shmem.c:shmem_replace_page",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:PageMovable",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__do_fault",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate_device.c:migrate_vma_pages",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:hwpoison_filter",
        "mm/zsmalloc.c:zs_page_migrate",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994544,
      "name": "page_mapping",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582431403,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/folio-compat.c:12",
      "file": "mm/folio-compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:__set_page_dirty_nobuffers"
      ],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/memory.c:__do_fault",
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:hwpoison_filter",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430672,
      "name": "page_mapping",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582636764,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/folio-compat.c:13",
      "file": "mm/folio-compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:__set_page_dirty_nobuffers"
      ],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/memory.c:__do_fault",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/memory-failure.c:hwpoison_filter",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/crypto/inline_crypt.c:fscrypt_set_bio_crypt_ctx_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635936,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582808136,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/folio-compat.c:13",
      "file": "mm/folio-compat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/folio-compat.c:__set_page_dirty_nobuffers"
      ],
      "caller_func": [
        "mm/debug.c:__dump_page",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/memory-failure.c:hwpoison_user_mappings",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/memory-failure.c:hwpoison_filter",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/crypto/inline_crypt.c:bh_get_inode_and_lblk_num"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807696,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492613520,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492613520,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226465284,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226465284,
      "name": "page_mapping",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285930656,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:delete_from_page_cache",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_mkclean",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:mark_buffer_dirty",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285930656,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272640108,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272640108,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193632,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193632,
      "name": "page_mapping",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140384,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140384,
      "name": "page_mapping",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184832,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184832,
      "name": "page_mapping",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct address_space * page_mapping(struct page * page)
```

```json
{
  "name": "page_mapping",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248080,
      "name": "page_mapping",
      "external": true,
      "loc": "mm/util.c:648",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:page_endio",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:__cancel_dirty_page",
        "mm/page-writeback.c:set_page_dirty",
        "mm/truncate.c:invalidate_inode_page",
        "mm/vmscan.c:page_evictable",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:page_mapping_file",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/debug.c:__dump_page",
        "mm/rmap.c:rmap_walk_file",
        "mm/rmap.c:page_add_file_rmap",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/khugepaged.c:collapse_file",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_pagecache_dirty",
        "mm/zsmalloc.c:zs_page_putback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_isolate",
        "fs/fs-writeback.c:perf_trace_track_foreign_dirty",
        "fs/fs-writeback.c:trace_event_raw_event_track_foreign_dirty",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:__set_page_dirty_buffers",
        "fs/iomap/buffered-io.c:iomap_set_page_dirty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248080,
      "name": "page_mapping",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
