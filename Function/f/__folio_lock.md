# Function: <code>__folio_lock</code>

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
void __folio_lock(struct folio * folio)
```

```json
{
  "name": "__folio_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581932580,
      "name": "__folio_lock",
      "external": true,
      "loc": "mm/filemap.c:1688",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:writeout",
        "mm/migrate.c:putback_movable_pages",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
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
      "addr": 18446744071581932160,
      "name": "__folio_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __folio_lock(struct folio * folio)
```

```json
{
  "name": "__folio_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582371023,
      "name": "__folio_lock",
      "external": true,
      "loc": "mm/filemap.c:1658",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:writeout",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memremap.c:zone_device_page_init",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
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
      "addr": 18446744071582369936,
      "name": "__folio_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __folio_lock(struct folio * folio)
```

```json
{
  "name": "__folio_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582575869,
      "name": "__folio_lock",
      "external": true,
      "loc": "mm/filemap.c:1632",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:writeout",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/memremap.c:zone_device_page_init",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
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
      "addr": 18446744071582574784,
      "name": "__folio_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __folio_lock(struct folio * folio)
```

```json
{
  "name": "__folio_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582744810,
      "name": "__folio_lock",
      "external": true,
      "loc": "mm/filemap.c:1612",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:__filemap_get_folio",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": [
        "kernel/futex/core.c:get_futex_key",
        "kernel/events/uprobes.c:__replace_page",
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:pageout",
        "mm/shmem.c:shmem_get_folio_gfp",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_get_partial_folio",
        "mm/gup.c:unpin_user_page_range_dirty_lock",
        "mm/gup.c:unpin_user_pages_dirty_lock",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_unmap",
        "mm/migrate.c:writeout",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb",
        "mm/memory-failure.c:try_to_split_thp_page",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/memremap.c:zone_device_page_init",
        "fs/pipe.c:generic_pipe_buf_try_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases",
        "fs/iomap/buffered-io.c:iomap_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page",
        "fs/fuse/file.c:fuse_page_mkwrite",
        "block/bio.c:bio_set_pages_dirty",
        "block/bio.c:__bio_release_pages",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744448,
      "name": "__folio_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void __folio_lock(struct folio * folio)
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
