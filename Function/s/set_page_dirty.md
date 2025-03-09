# Function: <code>set_page_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580519072,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2545",
      "file": "mm/page-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:end_swap_bio_write",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_truncate_page",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519072,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604576,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2589",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604576,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580671488,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2556",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671488,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704688,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2559",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704688,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790208,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2542",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790208,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925632,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2543",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925632,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581001632,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2537",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_shmem",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001632,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065904,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2545",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_shmem",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065904,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121872,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121872,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304544,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2559",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304544,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581347056,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2557",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581347056,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366032,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2557",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366032,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581614720,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2591",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614720,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
bool set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994448,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/folio-compat.c:82",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_writepage",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:end_swap_bio_write",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994448,
      "name": "set_page_dirty",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582430784,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/folio-compat.c:54",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_write_end",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:end_swap_bio_write",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430784,
      "name": "set_page_dirty",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582636064,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/folio-compat.c:55",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/page_io.c:sio_write_complete",
        "mm/page_io.c:__end_swap_bio_write",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "fs/libfs.c:simple_write_end",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636064,
      "name": "set_page_dirty",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807568,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/folio-compat.c:55",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/gup.c:follow_page_pte",
        "mm/page_io.c:sio_write_complete",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/ksm.c:write_protect_page",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807568,
      "name": "set_page_dirty",
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492499472,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492499472,
      "name": "set_page_dirty",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226364272,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/ksm.c:write_protect_page",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226364272,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285780320,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/truncate.c:pagecache_isize_extended",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285780320,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272554440,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272554440,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090720,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090720,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037904,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:zap_pte_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037904,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081920,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081920,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int set_page_dirty(struct page * page)
```

```json
{
  "name": "set_page_dirty",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144464,
      "name": "set_page_dirty",
      "external": true,
      "loc": "mm/page-writeback.c:2549",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/rmap.c:try_to_unmap_one",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:end_swap_bio_write",
        "mm/swap_state.c:add_to_swap",
        "mm/hugetlb.c:huge_add_to_page_cache",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/khugepaged.c:collapse_file",
        "mm/hmm.c:hmm_range_dma_unmap",
        "fs/libfs.c:simple_write_end",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:block_page_mkwrite",
        "fs/fuse/file.c:fuse_write_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144464,
      "name": "set_page_dirty",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
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
