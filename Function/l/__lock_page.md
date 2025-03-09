# Function: <code>__lock_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __lock_page(struct page * page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470544,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:874",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/balloon_compaction.c:balloon_page_putback",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:__generic_file_splice_read",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_truncate_page",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/crypto.c:ext4_encrypt",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470544,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void __lock_page(struct page * page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580548256,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:915",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/zsmalloc.c:lock_zspage",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/dax.c:dax_fault",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580548256,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614544,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1021",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/zsmalloc.c:lock_zspage",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/dax.c:grab_mapping_entry",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614544,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643920,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1147",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:lock_zspage",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643920,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726112,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1269",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:lock_zspage",
        "mm/hmm.c:hmm_vma_alloc_locked_page",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726112,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580861600,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1269",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:lock_zspage",
        "mm/hmm.c:hmm_vma_alloc_locked_page",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580861600,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931808,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1322",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "mm/hmm.c:hmm_vma_alloc_locked_page",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/crypto/crypto.c:fscrypt_encrypt_page",
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931808,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026112,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1370",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026112,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081456,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081456,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581281771,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1354",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268800,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581325752,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1539",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313776,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581337354,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1589",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332336,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585659,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1644",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580016,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492448088,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492448088,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226322528,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226322528,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285721136,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285721136,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272521512,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:__munlock_pagevec",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272521512,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050304,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050304,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580997584,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997584,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041504,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041504,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
void __lock_page(struct page * __page)
```

```json
{
  "name": "__lock_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103104,
      "name": "__lock_page",
      "external": true,
      "loc": "mm/filemap.c:1379",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/zsmalloc.c:async_free_zspage",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/pipe.c:generic_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/iomap/seek.c:page_cache_seek_hole_data",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103104,
      "name": "__lock_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page * __page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void __lock_page(struct page * __page)
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
