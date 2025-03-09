# Function: <code>__kunmap_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579945069,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121627,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219103,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580446788,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:copy_from_page",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580508317,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545621,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583518,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580665116,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743421,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760004,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swp_swapcount",
        "mm/swapfile.c:add_swap_count_continuation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780649,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830256,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580884506,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898885,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580965339,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974219,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020595,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581035129,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:__page_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158271,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_readpage",
        "fs/libfs.c:simple_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222074,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:nobh_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246624,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260975,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317965,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:do_io_submit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327105,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562599,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597899,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820990,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861143,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872580,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894602,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901522,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936557,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006974,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009872,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049040,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079695,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_short_read",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441365,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640421,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582650781,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657389,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582661886,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_compat_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716511,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863702,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938789,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583015466,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021302,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:memcpy_from_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583851777,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183882,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535812,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548148,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584562614,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584799253,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584872491,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_prepare",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585777303,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_file_clear_bit",
        "drivers/md/bitmap.c:bitmap_file_set_bit",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_print_sb",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_copy_from_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586211396,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579975903,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155618,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255919,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523292,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590282,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634792,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580680365,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802473,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863518,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580882446,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903765,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966386,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010071,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035462,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052970,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121766,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128158,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179043,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581323389,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388483,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413199,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426703,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492505,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498354,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583043,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581754566,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788762,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016732,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060445,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068166,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082016,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088684,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124056,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132098,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582140635,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142137,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143644,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222590,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223152,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264139,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295065,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663231,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582889671,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897750,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903574,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908346,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993448,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583149582,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583226143,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306377,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_to_iter",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584181298,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523004,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887495,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_make_request",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584898627,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919819,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159445,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235518,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586188073,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_file_clear_bit",
        "drivers/md/bitmap.c:bitmap_file_set_bit",
        "drivers/md/bitmap.c:bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586635500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580006413,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580196046,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586601,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657143,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701897,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746361,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580867509,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580933827,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950538,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580971778,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040132,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084151,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110628,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126547,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581196854,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203213,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222548,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256159,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402563,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581466963,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493840,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507916,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571477,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582260,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668323,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581842802,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878352,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106780,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150258,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158198,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172109,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178772,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582213829,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221839,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230335,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231827,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582233324,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312094,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312656,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353787,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383139,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756282,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986246,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994208,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583003302,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008068,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098403,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261530,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583332084,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337890,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425577,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583442028,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584362644,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705083,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585088421,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585103180,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585353269,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585431006,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586392217,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_file_clear_bit",
        "drivers/md/bitmap.c:bitmap_file_set_bit",
        "drivers/md/bitmap.c:bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586820908,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580013934,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203760,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616940,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689902,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735897,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781843,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913009,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977830,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993699,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581017217,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088264,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131956,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160907,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175794,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244390,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251142,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270391,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305501,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581457655,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522552,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548761,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559990,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627234,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643987,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722767,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581969770,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076999,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115061,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115889,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582258813,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265155,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299080,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307735,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315557,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316886,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318096,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396992,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397421,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437845,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468104,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848603,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036273,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044177,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583053324,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058528,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154771,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313508,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583390451,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396635,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446075,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465854,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584444282,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786480,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160429,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585184625,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435913,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515800,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585652291,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494155,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_file_clear_bit",
        "drivers/md/bitmap.c:bitmap_file_set_bit",
        "drivers/md/bitmap.c:bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586496985,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report",
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563613,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586935824,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272331,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:74",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580060862,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255152,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697596,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580822663,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868444,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012225,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080785,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099472,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126867,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200456,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581247240,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286263,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309552,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376988,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383042,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409429,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445283,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581599700,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664814,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693107,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703969,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771511,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789721,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868867,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582119002,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141947,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582228050,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264085,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265864,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407857,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414190,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448117,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582456903,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464743,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466074,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467472,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547716,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548462,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588305,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582619810,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583005471,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201748,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209569,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583219101,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224692,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329827,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496403,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569754,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576343,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626059,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583646739,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584853896,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206710,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587437,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585612847,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585866249,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947692,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084432,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962068,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965110,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report",
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031151,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587428880,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588828091,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579812560,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580118351,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315586,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829963,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910846,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959295,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004791,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581145857,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219797,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243610,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581269307,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345780,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346608,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391429,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448280,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526345,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533102,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565141,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604435,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581756745,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581828124,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581859963,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871315,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943947,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581963633,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051491,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582307645,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330969,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417830,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452321,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453603,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598170,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604807,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637840,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646788,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655774,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657995,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658460,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739017,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740539,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780874,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811285,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206127,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410228,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418744,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583427172,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432672,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539030,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710371,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583792492,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842139,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864915,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084984,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442870,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831886,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585859034,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586112677,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194870,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586332048,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256982,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_create",
        "drivers/md/md-bitmap.c:bitmap_daemon_work",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587260805,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report",
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329248,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587733964,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589206283,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:75",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579859312,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580165039,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368162,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813471,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899174,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985589,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035519,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080617,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225681,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303509,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327111,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352619,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429876,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430704,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474891,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499147,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531135,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608681,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619010,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651802,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689875,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581843225,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581915372,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944743,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956405,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029624,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046017,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582139418,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_write_end",
        "fs/iomap.c:iomap_read_page_sync",
        "fs/iomap.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406349,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429574,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517289,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551798,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553093,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699882,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706525,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739584,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748549,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757630,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759948,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760348,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842777,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844299,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884138,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582914231,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948896,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323071,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531940,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539176,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583548431,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554160,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661418,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583819058,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865630,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583871197,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_complete",
        "block/t10-pi.c:t10_pi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583925814,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583950951,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585189187,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195703,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566454,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966094,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585990567,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259013,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586329037,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586473648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587437721,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507584,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868124,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589447883,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579893528,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580211141,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420884,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902563,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996825,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099443,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144210,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299473,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371478,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390072,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438148,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463043,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542610,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:memcmp_pages",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543660,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589865,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608743,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641880,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720626,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731571,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768916,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808380,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967808,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582052529,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:guard_bio_eod",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080863,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089088,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169301,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582210394,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582303576,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575120,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598819,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684746,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724090,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725590,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872607,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879807,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913376,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582924183,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931890,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934178,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934592,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017863,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019432,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064669,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093642,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_short_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510587,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719908,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727280,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583737606,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743242,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848604,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009411,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055791,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061998,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_complete",
        "block/t10-pi.c:t10_pi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106137,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130061,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585405414,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408060,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785954,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209224,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586227353,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586503141,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579996,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586718589,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587710002,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781496,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588172128,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589905662,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943800,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580259541,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469636,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955745,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051241,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156383,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201746,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228135,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358241,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431182,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450296,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502372,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527139,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607509,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608556,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653529,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679642,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713001,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581794082,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804707,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841330,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880972,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582040896,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137401,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158303,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166518,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246693,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582291290,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582322946,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402600,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676080,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699555,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786922,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826620,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969159,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582979153,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986296,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019952,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583030745,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038466,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040792,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041216,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124055,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125624,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583205265,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235712,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616475,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829620,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836944,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583847366,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853034,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583951516,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584112912,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178127,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584184249,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230290,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584253255,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585542134,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548805,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929490,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357272,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586375577,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651029,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586727341,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865197,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914306,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587986200,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377328,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131646,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579263637,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266625,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271140,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968076,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580314858,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542115,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151508,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581276636,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581380028,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431866,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581459063,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600676,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673227,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704068,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758181,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783647,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870342,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871520,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581918006,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:copy_huge_page",
        "mm/migrate.c:__copy_gigantic_page",
        "mm/migrate.c:__copy_gigantic_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981942,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068158,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:find_alloced_obj",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:init_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152928,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326791,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411486,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582414438,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582446557,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582454496,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582539992,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_add_table",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646315,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684146,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763631,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583063456,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073397,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583178061,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583215360,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583221495,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401613,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403256,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419201,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455004,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465239,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472640,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474862,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475216,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583557059,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558536,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583633092,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675598,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584093307,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343438,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584354677,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361443,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584460388,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619289,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690990,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697336,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584754866,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776324,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter",
        "lib/iov_iter.c:copy_mc_pipe_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287086,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382874,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384997,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773988,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587247537,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587515733,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587579574,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729687,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786868,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588854959,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589064216,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242800,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:202",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579264748,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272527,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975667,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580318340,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545473,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292558,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316054,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581400943,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581451930,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479911,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623524,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718746,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725735,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785093,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810910,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900950,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902100,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942872,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582010988,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089351,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177117,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354711,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438286,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582441641,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582473359,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481555,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582569000,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_add_table",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676417,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714148,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796510,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088864,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098761,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583204687,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583242867,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583249350,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433781,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441368,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477436,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487258,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494908,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497139,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497424,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580311,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581973,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629747,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677556,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583696606,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701833,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120667,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377947,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584389029,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395909,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584495254,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719152,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584725435,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584783330,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584822538,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:iov_iter_zero",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:_copy_mc_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585070873,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170782,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267066,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269169,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654036,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109512,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134839,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397349,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463766,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/scsi/sd.c:sd_setup_unmap_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587608919,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672721,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588743893,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951319,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589137776,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:197",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579306165,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309939,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314701,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106996,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580472086,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717121,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537470,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561316,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581651866,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706410,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581734311,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages",
        "mm/util.c:copy_huge_page",
        "mm/util.c:copy_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581890980,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991111,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996442,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582068869,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096808,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195640,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196788,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246854,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313471,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401934,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_freepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413161,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494605,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675831,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582761070,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582764594,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785778,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582794573,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582886280,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_add_table",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993827,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040772,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113810,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583428576,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438465,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583548034,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583584957,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583589709,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583783096,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790798,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583831756,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583841714,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583849708,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851990,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852352,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583937361,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939989,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988703,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036458,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056751,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584062499,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502169,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584773179,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584784261,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791141,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584902410,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585212701,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585222401,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585518009,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624478,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777589,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780721,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200900,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682168,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587708060,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587969093,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041104,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588197308,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589350944,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434357,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589660567,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589856864,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:211",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360931,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367383,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372943,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580928831,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883076,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913100,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582108650,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115253,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288739,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394826,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582507863,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537375,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582639219,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660698,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917923,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:__zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926674,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019597,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454096,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_add_table",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463805,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515707,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946740,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584339138,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584353952,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584399453,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584410404,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584418874,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421635,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422156,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520733,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139101,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458065,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585471812,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586051252,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066011,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586670099,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783701,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504953,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589050075,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589331909,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589575987,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824727,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb"
      ]
    },
    {
      "addr": 18446744071590912065,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591386940,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs"
      ],
      "caller_func": [
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590807168,
      "name": "__kunmap_atomic.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071591381776,
      "name": "__kunmap_atomic.constprop.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581221479,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316196,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348172,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582589077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781392,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582901130,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583022951,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052808,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161235,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184453,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583466289,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:restore_freelist",
        "mm/zsmalloc.c:restore_freelist",
        "mm/zsmalloc.c:restore_freelist",
        "mm/zsmalloc.c:restore_freelist",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:find_tagged_obj",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043984,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_add_table",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055357,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573476,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584988401,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005555,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054253,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585068453,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077526,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191504,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863940,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216945,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586232180,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238620,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034868,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587059067,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589946297,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579243,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590898133,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591170435,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592512551,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592609892,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592885900,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593150556,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595749472,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595949989,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:227",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581315911,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517352,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551059,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582796437,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947649,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232119,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583262927,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376883,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402213,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687089,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281149,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216431,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231631,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585282317,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297797,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307142,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416181,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420559,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095879,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290020,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587315617,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic",
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590255561,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590920939,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591241733,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591529571,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592943002,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593040481,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593324508,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593604092,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596273779,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581422155,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582686232,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721651,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583879892,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:migrate_zspage",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:zs_object_copy",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497949,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531621,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541206,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344983,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575892,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587595183,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596537,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264795,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591588981,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591877043,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591957174,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/gpu/drm/drm_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_cache.c:drm_clflush_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593692781,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_new_disk_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593791986,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594081548,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594378684,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597158515,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:230",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490338184,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/arm64/kernel/probes/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490399900,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:__kvm_unmap_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491502084,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491744424,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492301296,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492408108,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492534344,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492584284,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492618600,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492761812,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492833476,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492856784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492923740,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492956028,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493047864,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493050644,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493103632,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493127348,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493159404,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493254872,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493269672,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493303460,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493351784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493566800,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493682640,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493712088,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720668,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493817308,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_read_events_ring",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493867460,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493904228,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494003016,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494329072,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494356688,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494456676,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494498012,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494500944,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494645544,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494658560,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494671536,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494713324,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494726764,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494734396,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494736592,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494737272,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494834180,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494835340,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494889584,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494918560,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494958724,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495399564,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495640788,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495649492,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495661040,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495668816,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495771148,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496042944,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496049304,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496103500,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496131052,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498203956,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498210708,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752468,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499203240,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499222200,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499548960,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499637628,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499798880,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501145932,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501231236,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501888848,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __kunmap_atomic(void * kvaddr)
```

```json
{
  "name": "__kunmap_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224509004,
      "name": "__kunmap_atomic",
      "external": true,
      "loc": "arch/arm/mm/highmem.c:99",
      "file": "arch/arm/mm/highmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault.c:show_pte",
        "arch/arm/mm/dma-mapping.c:dma_cache_maint_page",
        "arch/arm/mm/dma-mapping.c:__dma_clear_buffer",
        "arch/arm/mm/pgd.c:pgd_alloc",
        "arch/arm/mm/pgd.c:pgd_alloc",
        "arch/arm/mm/copypage-v6.c:v6_clear_user_highpage_nonaliasing",
        "arch/arm/mm/copypage-v6.c:v6_copy_user_highpage_nonaliasing",
        "arch/arm/mm/copypage-v6.c:v6_copy_user_highpage_nonaliasing",
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_flush_range",
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_flush_range",
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_clean_range",
        "arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_inv_range",
        "arch/arm/probes/uprobes/core.c:arch_uprobe_copy_ixol",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:restore_highmem",
        "kernel/power/snapshot.c:copy_last_highmem_page",
        "kernel/power/snapshot.c:snapshot_read_next",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:swsusp_save",
        "kernel/power/snapshot.c:clear_free_pages",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/debug/kdb/kdb_support.c:kdb_getphys",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_referenced_one",
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:swp_swapcount",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:calc_checksum",
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage",
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/direct-io.c:do_direct_IO",
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring",
        "fs/verity/verify.c:extract_hash",
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor",
        "fs/iomap/buffered-io.c:iomap_read_inline_data",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin",
        "fs/ext4/move_extent.c:mext_page_mkuptodate",
        "fs/ext4/page-io.c:ext4_bio_write_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/verity.c:pagecache_read",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/readdir.c:fuse_emit",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/scatterwalk.c:scatterwalk_copychunks",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:crypto_hash_walk_done",
        "crypto/shash.c:shash_ahash_digest",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:copy_to_high_bio_irq",
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process",
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare",
        "block/t10-pi.c:t10_pi_type1_prepare",
        "lib/scatterlist.c:sg_miter_stop",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page",
        "lib/iov_iter.c:copy_page_to_iter_iovec",
        "lib/iov_iter.c:copy_page_to_iter_iovec",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor",
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb",
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error",
        "drivers/mmc/host/sdhci.c:sdhci_finish_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224509004,
      "name": "__kunmap_atomic",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284462372,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284778224,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285537844,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285673352,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285830124,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285903336,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285935992,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286127220,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286220448,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286248152,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286327568,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286368252,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286487188,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286488972,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286563888,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286607088,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286656728,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286784208,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286796544,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286846080,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286901968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287141148,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287285572,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287317484,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287326392,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287436120,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287497164,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287541456,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287651444,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288053160,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288086968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288210076,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288263396,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288266224,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288457476,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288472776,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288484136,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288535388,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288549672,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288559544,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288562676,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288563156,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288680648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288681988,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288751948,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288794944,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288835348,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289428928,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289771992,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289783172,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289798432,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289808032,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289945648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290273364,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290282592,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290349732,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290381068,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291915968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292406700,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292842152,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292958728,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293153040,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294653208,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294759960,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295296836,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272430820,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272585408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272621280,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272643840,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272742408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272787426,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272803968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272843780,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272868784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272917246,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272918336,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272951408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273012524,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022916,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273046758,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273079100,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273223872,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273305934,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273326314,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273332078,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273399616,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_complete",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273431700,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273460502,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273516996,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273765338,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273786004,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273864368,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896884,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273898792,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274013718,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274022958,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274030648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274064590,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274074350,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274081504,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083372,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083792,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274157588,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274158546,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274204774,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274232032,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274261092,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274599688,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274795526,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274803280,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274812938,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274819506,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274918228,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275120676,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275127496,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275169876,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275189876,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276256894,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276493730,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276748608,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276820362,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276950878,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277858702,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277925750,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278206342,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911576,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580228341,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438436,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924545,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020089,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125231,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170594,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581196983,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327089,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400030,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419144,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471108,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581495875,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576245,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577292,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622265,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648378,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681737,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762818,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773443,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810066,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849708,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582009632,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106137,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127039,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135254,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215429,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260026,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582291682,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582371336,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582644816,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582668291,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755658,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795356,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797238,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937895,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582947889,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955032,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988688,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999481,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007202,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009528,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009952,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092791,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094360,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142813,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174001,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204448,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585211,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583798356,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805680,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583816102,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821770,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920252,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584081648,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146863,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584152985,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584199026,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584221991,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585304166,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310837,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690466,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119160,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137993,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586341509,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417821,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586623725,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545282,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587617176,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587984112,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733902,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579850808,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580175829,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580385508,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870604,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966185,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072207,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117410,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143735,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270849,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342542,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361656,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413364,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438115,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517813,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518860,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563561,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591207,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620401,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581701442,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711846,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747730,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787372,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581947200,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043577,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582064479,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072694,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152315,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196943,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582229442,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309032,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582581984,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605459,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582692826,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732508,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734390,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875047,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582885041,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892184,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925840,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936633,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944354,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582946680,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947104,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029943,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031512,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079965,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111153,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583141600,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522267,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735412,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742736,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583753158,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758826,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857212,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584017408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082399,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584088249,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134242,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157207,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550162,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586101066,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:pmem_do_bvec",
        "drivers/nvdimm/pmem.c:write_pmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586107736,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/nvdimm/btt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/btt.c:btt_write_pg",
        "drivers/nvdimm/btt.c:btt_read_pg",
        "drivers/nvdimm/btt.c:btt_read_pg",
        "drivers/nvdimm/btt.c:btt_rw_integrity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586116527,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/nvdimm/blk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586182837,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294077,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586492237,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313378,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587385192,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587697216,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459582,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579904072,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580219813,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580429684,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915793,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011289,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116431,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161794,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188183,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318289,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391230,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410344,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462420,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487187,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567557,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568604,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613577,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639690,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673049,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754130,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764755,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801378,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841020,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582000912,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096617,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117519,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125734,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205909,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250506,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582282162,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361816,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634672,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658147,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745514,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784236,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786118,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926503,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582936497,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943640,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582977296,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988089,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995810,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998136,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998560,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081399,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082968,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126845,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583158033,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583188480,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568987,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782116,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789440,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583799862,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805530,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904012,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584065408,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130623,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136745,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584182786,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205751,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492534,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499205,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879714,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305240,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323545,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586598997,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681901,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586819757,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587870450,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587942344,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588315888,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177278,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
  "name": "__kunmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579950127,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580272612,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485283,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975864,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072532,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178862,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228040,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251461,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382341,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_user_huge_page",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:copy_subpage",
        "mm/memory.c:clear_huge_page",
        "mm/memory.c:clear_subpage",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581455120,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475438,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:prep_new_page",
        "mm/page_alloc.c:__free_pages_ok",
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523603,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:swap_count_continued",
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:swp_swapcount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552861,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632515,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633607,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681355,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705967,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740287,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825923,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833603,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870554,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910531,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582072119,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_write_end",
        "fs/libfs.c:simple_write_begin",
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169487,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:cont_write_begin",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190486,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198733,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280157,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:aio_read_events",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:aio_setup_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582330806,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582360729,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441519,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end",
        "fs/iomap/buffered-io.c:iomap_read_page_sync",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582717967,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_journalled_write_inline_data",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_readpage_inline",
        "fs/ext4/inline.c:ext4_read_inline_page",
        "fs/ext4/inline.c:ext4_read_inline_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741814,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_journalled_zero_new_buffers",
        "fs/ext4/inode.c:ext4_block_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830769,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870611,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872518,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013559,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583024028,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031784,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066095,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077200,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583084946,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086996,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087628,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170734,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172259,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220404,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251701,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_ioctl",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepage_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583282985,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666130,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583883119,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890472,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583900893,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906581,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004893,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584168230,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234678,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240848,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287183,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310286,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600541,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607244,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988921,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586416710,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435120,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586711285,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787924,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586925876,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985545,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057631,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451884,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_ts_finish",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_seq_read",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227733,
      "name": "__kunmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:99",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void __kunmap_atomic(void * kvaddr)
```
</details>
</li>
</ul>
