# Function: <code>lock_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579892402,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448618,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474235,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519199,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543227,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551996,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580586343,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663288,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692220,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764014,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807797,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830561,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885394,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949757,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972513,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_putback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026988,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198244,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:__generic_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227506,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_truncate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541507,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564243,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881483,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940123,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008472,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081552,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511940,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:454",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924230,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523868,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554263,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604767,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580631983,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580643164,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580682951,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766595,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774435,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807257,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891839,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932215,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938140,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962900,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017275,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040815,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105159,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120721,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186116,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363891,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:__generic_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396359,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498031,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502749,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581688,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727297,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581784373,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154064,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221656,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294352,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833657,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:431",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954886,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587193,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619059,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580671679,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699215,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710236,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580749998,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832158,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849022,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872307,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960242,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000512,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009886,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036560,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091498,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115983,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180318,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195825,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222350,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581263332,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437328,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474705,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581258,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:grab_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587946,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581670568,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813841,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581873925,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243486,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311192,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382736,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972905,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:450",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void lock_page(struct page * page)
```

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579959795,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617197,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648836,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580704879,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732715,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580744794,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580785385,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872808,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894410,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917312,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006386,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043590,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057280,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084376,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138578,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    },
    {
      "addr": 18446744071581164170,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228955,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243361,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270047,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581312420,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491968,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533048,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648545,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581724631,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930851,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582021961,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328727,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396056,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467715,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584021466,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128976,
      "name": "lock_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void lock_page(struct page * page)
```

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006732,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697949,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732655,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790399,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819391,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580831965,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580874715,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969310,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991975,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016720,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119210,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154103,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581196095,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260189,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    },
    {
      "addr": 18446744071581284658,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360088,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375041,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388879,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409044,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581452452,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633920,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675725,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:page_cache_seek_hole_data",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581793985,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870667,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172569,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479020,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546744,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618451,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584237386,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581241920,
      "name": "lock_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580058768,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830320,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868079,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926805,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580956453,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969088,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581011133,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099082,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125598,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151175,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255509,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297204,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341748,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405551,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431830,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507888,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524945,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539855,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564606,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581612020,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792519,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835982,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581968277,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047331,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362464,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670797,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738430,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813699,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457913,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106098,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897587,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939246,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001813,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032437,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045826,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581084903,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181864,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192672,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231004,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338783,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380500,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425816,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489019,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515315,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593818,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610100,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625855,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650830,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698372,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879415,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581923244,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055189,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141214,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461472,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771699,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842190,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582916995,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584554441,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:479",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580150965,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995128,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033600,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066101,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096437,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109295,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581151463,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252284,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265536,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305428,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449174,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491851,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538092,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598097,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626478,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705411,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721487,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768661,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816087,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004329,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060534,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299051,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311133,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630525,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945718,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017267,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095236,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752266,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:466",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580198623,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049109,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089168,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122069,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153349,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166287,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581209351,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310892,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324384,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364004,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487026,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513398,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556331,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602988,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668657,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697331,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776883,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794943,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841073,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888647,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082281,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138326,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398043,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410189,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731661,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052374,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123459,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198148,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887050,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580267055,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231771,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281335,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304741,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339498,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359485,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391705,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581500620,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515466,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561242,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692284,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722008,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766517,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819839,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888291,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913018,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000715,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582017602,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062174,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582115938,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320153,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373503,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688364,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703934,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040025,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370969,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443763,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583527256,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583817,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:517",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580250992,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274366,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325319,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347264,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381482,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402896,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440153,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540789,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560394,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606218,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737162,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770095,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581814676,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867731,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934270,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958702,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046967,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066050,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162370,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373545,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411230,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582429792,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759612,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775214,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115809,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486969,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557171,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637400,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716713,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:606",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580256132,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291006,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337038,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366240,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581402207,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420720,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460985,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584026,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628890,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765482,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797458,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842764,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581898382,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959717,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992118,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072073,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090754,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186882,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400841,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438030,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582456576,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788524,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141505,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509116,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580419,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658328,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597145,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:622",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580407441,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535296,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585343,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614912,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655285,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671254,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713784,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849706,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896698,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048149,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081833,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134127,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582193095,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264546,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294312,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380009,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure_hugetlb",
        "mm/memory-failure.c:memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582403381,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504258,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722361,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760814,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582778934,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583116668,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482037,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864137,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938435,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016968,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073001,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:621",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580624650,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884215,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976031,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262604,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479141,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520443,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582582578,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655545,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732833,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:writeout",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780324,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883985,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032171,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271394,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583335250,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006303,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584437980,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584518946,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584608627,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587296151,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:956",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580890538,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410991,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582754457,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992728,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109126,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178902,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250453,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278116,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583312388,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438899,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_memory_failure_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496273,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583596507,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583854562,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583919919,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636425,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189554,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287744,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588536631,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:952",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580974432,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582617439,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969945,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395199,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497588,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658066,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_to_split_thp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711281,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813331,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072733,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585418594,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518022,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588816439,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:973",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582788959,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635587,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690737,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_coherent_page",
        "mm/migrate_device.c:migrate_device_coherent_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583860560,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:try_to_split_thp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583911649,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:zone_device_page_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019312,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585653378,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585754918,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109175,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1062",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491432816,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406056,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492455536,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492499816,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492530972,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492550168,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492594924,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492720444,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492730792,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492769660,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492906372,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492935552,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492993256,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493043172,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493112420,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493141404,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493236808,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493256456,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493303172,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493366332,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493621896,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493683512,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493999028,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494013772,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494388524,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494751224,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494833420,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494920104,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283212,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225426180,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3226290460,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226329372,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365192,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226396844,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226423568,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450324,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226561368,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3226586692,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 3226722644,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226759212,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226807648,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226866280,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226907896,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 3226954308,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227163104,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227215908,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 3227464132,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3227479280,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3227826676,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3228252036,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228330040,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3230461140,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284379664,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285670456,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285731568,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285780720,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285825888,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285852416,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285909368,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286063348,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286077056,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286134944,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286308360,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286346696,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286415280,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286482496,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286584952,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286624692,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286754368,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286781432,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286845732,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286911904,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287204080,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287286388,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287647436,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287664672,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288128860,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288579996,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288679684,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288785308,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291265288,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271894614,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272527114,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272554652,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272582994,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272593332,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272627624,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272719526,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272745052,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853628,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272894648,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272913734,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272957600,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273014170,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273046468,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273086136,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273261160,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273306634,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273514234,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273524600,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273812720,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274094308,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274156818,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274226884,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275816042,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580167423,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017957,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058016,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090917,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122197,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135135,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581178199,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279740,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293232,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332852,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581455874,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482134,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525067,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571724,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637393,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666067,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745619,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763679,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809809,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857383,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051017,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107062,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366779,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378925,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700397,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021110,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092195,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166884,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838234,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580115039,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964085,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005258,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038101,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069173,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082079,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581124999,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227797,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237648,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276564,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397975,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424415,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467088,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513292,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578353,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606341,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684243,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702303,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747473,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794983,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988569,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044502,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582304475,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316621,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637565,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958262,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029347,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104036,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768058,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580158895,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009157,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049216,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082117,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113397,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126335,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581169399,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270940,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284432,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324052,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447074,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473446,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516379,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563036,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628705,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657379,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736931,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754991,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801121,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848695,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042297,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097542,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357259,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369405,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582690253,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009718,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080803,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150916,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839658,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580212766,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070418,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110876,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144661,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175861,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188872,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581232182,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334821,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348382,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388031,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511536,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538231,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581381,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628024,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695006,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581723763,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805187,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581826781,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870275,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918197,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114014,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582170446,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:clean_bdev_aliases"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436879,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449071,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774557,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_page_mkwrite",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/inode.c:__ext4_journalled_writepage",
        "fs/ext4/inode.c:ext4_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099398,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170146,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245172,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944730,
      "name": "lock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:476",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_work",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void lock_page(struct page * page)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void lock_page(struct page * page)
```
</details>
</li>
</ul>
