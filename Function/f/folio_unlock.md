# Function: <code>folio_unlock</code>

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
void folio_unlock(struct folio * folio)
```

```json
{
  "name": "folio_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581941879,
      "name": "folio_unlock",
      "external": true,
      "loc": "mm/filemap.c:1552",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio"
      ],
      "caller_func": [
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/readahead.c:read_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:folio_referenced",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "fs/libfs.c:simple_read_folio",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_read_full_folio",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/fuse/dir.c:fuse_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922928,
      "name": "folio_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void folio_unlock(struct folio * folio)
```

```json
{
  "name": "folio_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582376895,
      "name": "folio_unlock",
      "external": true,
      "loc": "mm/filemap.c:1520",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:page_endio",
        "mm/filemap.c:page_endio"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:folio_write_one",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/readahead.c:read_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pagevec",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:folio_referenced",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "fs/libfs.c:simple_read_folio",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/jbd2/commit.c:release_buffer_page",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dir.c:fuse_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582360016,
      "name": "folio_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void folio_unlock(struct folio * folio)
```

```json
{
  "name": "folio_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582585140,
      "name": "folio_unlock",
      "external": true,
      "loc": "mm/filemap.c:1524",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/readahead.c:read_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_try_invalidate",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_read_folio_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:folio_referenced",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:release_pte_folio",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "fs/libfs.c:simple_read_folio",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:block_read_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__getblk_slow",
        "fs/buffer.c:end_buffer_async_read",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:mpage_read_end_io",
        "fs/mpage.c:mpage_read_end_io",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/iomap/buffered-io.c:iomap_read_end_io",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_process_page_bufs",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/ext4/readpage.c:__read_end_io",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dir.c:fuse_symlink_read_folio",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563296,
      "name": "folio_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void folio_unlock(struct folio * folio)
```

```json
{
  "name": "folio_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582756564,
      "name": "folio_unlock",
      "external": true,
      "loc": "mm/filemap.c:1471",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:next_uptodate_folio",
        "mm/filemap.c:next_uptodate_folio",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__filemap_get_folio"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_cache_pages",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/folio-compat.c:unlock_page",
        "mm/readahead.c:read_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:mapping_try_invalidate",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_read_mapping_page_gfp",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_splice_read",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_begin",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse_inode",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_read_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:fault_dirty_shared_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:folio_referenced",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/page_io.c:swap_read_folio",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:sio_read_complete",
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "mm/page_io.c:swap_writepage_fs",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:swap_writepage",
        "mm/page_io.c:__end_swap_bio_read",
        "mm/page_io.c:__end_swap_bio_read",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_swap_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:__try_to_reclaim_swap",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_folio",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:me_swapcache_clean",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_swapcache_dirty",
        "mm/memory-failure.c:me_pagecache_clean",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_read_folio",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_write_full_folio",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:__block_write_full_folio",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/buffer.c:__getblk_slow",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/mpage.c:mpage_read_end_io",
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_writepage_map",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_delalloc_release",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/iomap/buffered-io.c:iomap_read_folio",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_wait_for_tail_page_commit",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:mpage_map_and_submit_buffers",
        "fs/ext4/inode.c:mpage_process_page_bufs",
        "fs/ext4/inode.c:mpage_release_unused_pages",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dir.c:fuse_symlink_read_folio",
        "fs/fuse/file.c:fuse_writepages_fill",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734432,
      "name": "folio_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void folio_unlock(struct folio * folio)
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
