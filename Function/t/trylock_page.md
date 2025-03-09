# Function: <code>trylock_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579892407,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448623,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474022,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580519204,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580531734,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580543232,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552001,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_active_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586348,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657144,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663293,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_page_mkwrite",
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580692225,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730117,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756391,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swap_state.c:free_pages_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580764019,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:scan_swap_map",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580806573,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830566,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885399,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897838,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930707,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949762,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
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
      "addr": 18446744071580971909,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue",
        "mm/balloon_compaction.c:balloon_page_isolate",
        "mm/balloon_compaction.c:balloon_page_putback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975926,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581026993,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198249,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
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
      "addr": 18446744071581227511,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_page_mkwrite",
        "fs/buffer.c:nobh_truncate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326535,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541512,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564248,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
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
      "addr": 18446744071581881488,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/ext4/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/crypto.c:ext4_encrypt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905248,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940128,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008477,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081557,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583511945,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:446",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579924235,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523873,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554268,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604772,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618086,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580631988,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580658923,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580682956,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766600,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774440,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807262,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848765,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871880,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877199,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878737,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891844,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930590,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938145,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962905,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015428,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040820,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052174,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076848,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105164,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
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
      "addr": 18446744071581119057,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126369,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129915,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581186121,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363896,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
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
      "addr": 18446744071581396364,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:block_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498036,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502754,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581693,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727302,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581784378,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
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
      "addr": 18446744071582091777,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582154069,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221661,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294357,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833662,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:422",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579954891,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587198,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580619064,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580671684,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580685158,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580699220,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580726139,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580750003,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832163,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849937,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872312,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919245,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939768,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945235,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580946815,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960247,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998893,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009891,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036565,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089774,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115988,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132373,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581152448,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180323,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
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
      "addr": 18446744071581194162,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201409,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205003,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581222355,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581263337,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437333,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474710,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
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
      "addr": 18446744071581581263,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:grab_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587951,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581670573,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813846,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581873930,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
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
      "addr": 18446744071582181877,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243491,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311197,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382741,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972910,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:441",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579959800,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617202,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580648841,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580704884,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718678,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580732720,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761995,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785390,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872813,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895326,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917317,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963514,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983998,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989480,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580991438,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006391,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047586,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057285,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084381,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581137180,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164175,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175197,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199776,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228960,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
      "addr": 18446744071581241626,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248852,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253803,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581270052,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581312425,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491973,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533053,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
      "addr": 18446744071581648550,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581724636,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930856,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/ext4/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582021966,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
      "addr": 18446744071582268378,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582328732,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396061,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467720,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584021471,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580006737,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697954,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732660,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790404,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804214,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580819396,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849368,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580874720,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969315,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993080,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016725,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065834,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087011,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093198,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095422,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119215,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158251,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581196100,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254067,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581290703,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308778,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329696,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360093,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581373269,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380548,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385867,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581388884,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409049,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581452457,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633925,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675730,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581793990,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870672,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172574,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071582417453,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582479025,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546749,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582618456,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584237391,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580058773,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830325,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868084,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926820,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941126,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580956458,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985826,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011138,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099087,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127294,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151180,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204712,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229964,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233915,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236127,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255514,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301447,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341753,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400279,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437738,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447565,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477672,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507893,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581524757,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530548,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536345,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581539860,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564611,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581612025,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581792524,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835987,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581968282,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047336,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362469,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071582608058,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670802,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738435,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813704,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457918,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106103,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897592,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939251,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001828,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017030,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581032442,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062885,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084908,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181869,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192677,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231009,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288424,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312942,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316944,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319535,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338788,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581385088,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425821,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581483905,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521370,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532292,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560008,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593823,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071581610105,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616340,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622393,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581625860,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_alloc_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650835,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581698377,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879420,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581923249,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071582055194,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/crypto/crypto.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/crypto/crypto.c:fscrypt_encrypt_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141219,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:page_cache_seek_hole_data",
        "fs/iomap.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461477,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
      "addr": 18446744071582709813,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771704,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842195,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917000,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584554446,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:470",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580150970,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995133,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033605,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581066117,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080967,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581096442,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127000,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151468,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252289,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265541,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305433,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362833,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423719,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581427896,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430590,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449179,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581496638,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538097,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596210,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581630314,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642383,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674017,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705416,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:me_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721492,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581728002,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734814,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581768666,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816092,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004334,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060539,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
      "addr": 18446744071582299056,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311138,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630530,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
      "addr": 18446744071582883205,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945723,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017272,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095241,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752271,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:457",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580198628,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049114,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581089173,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122085,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136951,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581153354,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581184888,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209356,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310897,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324389,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364009,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422513,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485111,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492136,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494814,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513403,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561166,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602993,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663082,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701205,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713846,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746273,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776888,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071581794948,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801554,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808334,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581841078,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888652,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082286,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582138331,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582398048,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410194,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731666,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582989748,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052379,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123464,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198153,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887055,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580267060,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231776,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281340,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304757,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321527,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581339503,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369495,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391710,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581500625,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515471,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561247,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624357,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690338,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697950,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701021,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722013,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771590,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_page_mapping_lock_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819844,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874663,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917114,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931899,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967145,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582000720,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
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
      "addr": 18446744071582017607,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582022531,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582028162,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582062179,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582115943,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320158,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373508,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
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
      "addr": 18446744071582688369,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703939,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040030,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
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
      "addr": 18446744071583300022,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583370974,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583443768,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583527261,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583822,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:508",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580250997,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274371,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581325324,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read_pagenotuptodate",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:__wait_on_page_locked_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347269,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363383,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581381487,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
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
      "addr": 18446744071581413173,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page_prepare",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440158,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540794,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560399,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606223,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670597,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740082,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744647,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748525,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770100,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819766,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867736,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920855,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963818,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982463,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016042,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046972,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
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
      "addr": 18446744071582066055,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070963,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076914,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582162375,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582373550,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411235,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582429797,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
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
      "addr": 18446744071582759617,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775219,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115814,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
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
      "addr": 18446744071583414918,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486974,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557176,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637405,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716718,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:597",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580256137,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291011,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337043,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366245,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382375,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402212,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434402,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460990,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564667,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584031,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628895,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692821,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768366,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772810,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581776317,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797463,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848864,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581898387,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945831,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991266,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009516,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041854,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072078,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
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
      "addr": 18446744071582090759,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095939,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582103346,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582186887,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582400846,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438035,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582456581,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
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
      "addr": 18446744071582788529,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141510,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
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
      "addr": 18446744071583437766,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509121,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580424,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658333,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585597150,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:613",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int trylock_page(struct page * page)
```

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580407446,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535301,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585348,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:next_uptodate_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_update_page",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:__lock_page_async"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581614917,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631431,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/readahead.c:read_cache_pages_invalidate_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655290,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687483,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:pageout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713789,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581829435,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849711,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071581896703,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964775,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051022,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055433,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058959,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582081838,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582140105,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582193100,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250471,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:__unmap_and_move",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293426,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311952,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349566,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380014,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
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
      "addr": 18446744071582403386,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:trylock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409267,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419458,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582504263,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722366,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_try_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760819,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582778939,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
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
      "addr": 18446744071583116680,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482042,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
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
      "addr": 18446744071583787190,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864142,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583938440,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584016973,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586073006,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:612",
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
      "addr": 18446744071581847616,
      "name": "trylock_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582052751,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192315,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264178,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476552,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496548,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582514488,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582592071,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656005,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582726544,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740242,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582779313,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_in_file",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798200,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918771,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582921242,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:911",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582678912,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582737486,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993671,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583110643,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179413,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249576,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270912,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313572,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339745,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583473107,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476630,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:907",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582956983,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395710,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491328,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532916,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561426,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600379,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690707,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693350,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:928",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583132812,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_nonpresent_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583636092,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583690384,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751077,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797089,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583885107,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583887734,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:1017",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491432820,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406060,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492455540,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492499820,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492511828,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492530976,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492565620,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492594928,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492720448,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492730796,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492769664,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492823160,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903300,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492911056,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492914628,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492935556,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492994400,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493043176,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493109820,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493145040,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493159224,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493199456,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493236808,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446603336493256460,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493267448,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493273192,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493303180,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493366336,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493621900,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493683516,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446603336493999032,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494013776,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494388528,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446603336494674848,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494751228,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494833424,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494920108,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283216,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225426184,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3226290464,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226329376,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365196,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226381048,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226396848,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226427880,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450328,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226551124,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226561372,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3226586696,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 3226629860,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 3226695580,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226702760,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226705848,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 3226722648,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226759216,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226806400,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226830836,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226866284,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3226875000,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 3226879420,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226907932,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 3226954312,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227163108,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 3227215912,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 3227464136,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3227479292,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3227826680,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 3228115048,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 3228252040,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228330044,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 3230461144,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284379672,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285670464,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285731576,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285780732,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285799432,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285825896,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285872924,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285909376,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286063356,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286077064,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286134952,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286207360,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286305996,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286316544,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286320904,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286346704,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286417064,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286482504,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286579936,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286633284,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286654660,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286703296,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286754376,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 13835058055286781440,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286792432,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue",
        "mm/balloon_compaction.c:balloon_page_enqueue_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286801056,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286845740,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286911920,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287204096,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287286396,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 13835058055287647444,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287664680,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288128868,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 13835058055288488224,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288580004,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288679692,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288785316,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291265296,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271894622,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272527122,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272554660,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272569152,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272583002,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272609122,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272627632,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272713756,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272719534,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272745052,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272780400,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272827860,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272834568,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272837132,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853628,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:__try_to_reclaim_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272897882,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272913742,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272956494,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272978674,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273014170,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273020608,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273025172,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273046476,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273086144,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273261168,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273306642,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446743936273514242,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273524608,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273812728,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446743936274033792,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274094316,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274156826,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274226892,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275816042,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580167428,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017962,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058021,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090933,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105799,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581122202,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153736,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178204,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279745,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293237,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332857,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391361,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453959,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460984,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463662,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482139,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529902,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571729,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631818,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669941,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682582,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715009,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745624,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071581763684,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770290,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777070,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581809814,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857388,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051022,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107067,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582366784,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378930,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700402,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582958484,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021115,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092200,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166889,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838239,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580115044,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964090,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581005263,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581038117,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052871,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581069178,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100604,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125004,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227802,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237653,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276569,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334065,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396283,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403176,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405838,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424420,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471735,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513297,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581572874,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609477,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621224,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653921,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581684248,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071581702308,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708914,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715230,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581747478,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794988,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988574,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044507,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582304480,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316626,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637570,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582895636,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958267,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029352,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104041,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584768063,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580158900,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009162,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049221,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082133,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096999,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581113402,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144936,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169404,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270945,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284437,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324057,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382561,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445159,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452184,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454862,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473451,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521214,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563041,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623130,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581661253,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673894,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706321,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736936,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071581754996,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761602,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768382,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581801126,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848700,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042302,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:page_cache_pipe_buf_confirm",
        "fs/splice.c:page_cache_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097547,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582357264,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369410,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582690258,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071582947092,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009723,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080808,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150921,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839663,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
  "name": "trylock_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580212766,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070418,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110876,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_page_mkwrite",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144661,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:set_page_dirty_lock",
        "mm/page-writeback.c:write_cache_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159207,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/readahead.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581175861,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:invalidate_mapping_pages",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207441,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232182,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334821,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348382,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__do_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:do_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388031,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446449,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_referenced"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509640,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581516648,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_io.c:swap_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519310,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:free_page_and_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538231,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586156,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628024,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689461,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727621,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740003,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773713,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_account"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805187,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:async_free_zspage",
        "mm/zsmalloc.c:zs_malloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830482,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/balloon_compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/balloon_compaction.c:balloon_page_list_dequeue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837230,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581870275,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_steal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114014,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449071,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/iomap/seek.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/seek.c:page_cache_seek_hole_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774557,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
      "addr": 18446744071583035416,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099398,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:remove_inode_hugepages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170146,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_get_locked_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245172,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_page_mkwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944730,
      "name": "trylock_page",
      "external": false,
      "loc": "include/linux/pagemap.h:467",
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int trylock_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int trylock_page(struct page * page)
```
</details>
</li>
</ul>
