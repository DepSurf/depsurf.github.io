# Function: <code>kmap_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579945015,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580121580,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218824,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580446717,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580508306,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545587,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580583462,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580665034,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580743408,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580759902,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580780551,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580830174,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580884510,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580898424,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580964095,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/zsmalloc.c:zs_compact"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973184,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020678,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581035118,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:__page_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158243,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581221993,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581246684,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260881,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317908,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581327042,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault",
        "fs/dax.c:__dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562529,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581597761,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820974,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861067,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581871840,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894492,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901245,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936544,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582006892,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582009868,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048961,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582079676,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582441240,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640003,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582656997,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582661822,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_compat_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716460,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863501,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938629,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583016096,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583021243,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:memcpy_from_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter_iovec",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:copy_page_to_iter_iovec"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583851766,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183784,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535444,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547998,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584562534,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584801641,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584872482,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_prepare",
        "drivers/scsi/sd_dif.c:sd_dif_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585777241,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "drivers/md/bitmap.c:bitmap_copy_from_slot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586211385,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_bits",
        "net/core/skbuff.c:skb_store_bits",
        "net/core/skbuff.c:__skb_checksum",
        "net/core/skbuff.c:skb_copy_and_csum_bits",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579975847,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580155572,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255632,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523247,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580590255,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634763,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580680299,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580802450,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863522,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580882349,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580903679,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580966302,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581010054,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581035449,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052951,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581122506,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126993,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179127,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581323361,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581388451,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581413021,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426613,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491676,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581498298,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583013,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581754529,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581788626,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016716,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060383,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582068150,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081905,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088412,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582124011,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582132010,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582140572,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142128,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143556,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222566,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582223148,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263927,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582295038,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582663112,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582889641,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897675,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908282,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993404,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583149389,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583225953,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307031,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583318510,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584181277,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584522909,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887411,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_make_request",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec",
        "drivers/block/brd.c:brd_do_bvec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584898478,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919136,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585161791,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235509,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586188064,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
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
      "addr": 18446744071586644182,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580006331,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580195994,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586559,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580657129,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701869,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580746299,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580867496,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580933818,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950461,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580971695,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581040046,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581084138,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581110632,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127641,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581197578,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581202042,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222539,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256248,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402535,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581466931,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581493680,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507829,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570553,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581582212,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581668293,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581842765,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581878221,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106764,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150198,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582158182,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172001,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178510,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582213769,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582221754,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230426,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231818,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582233236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312070,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582312652,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353577,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582383123,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582756169,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986214,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994139,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583002904,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008010,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098345,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261324,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583331890,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337881,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426353,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583441893,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584362633,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584704989,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585088269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585102496,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585355612,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585430997,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586392208,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
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
      "addr": 18446744071586828870,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580013852,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203677,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616672,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580689851,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735830,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781791,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912952,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071580977821,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993615,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581017135,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581088178,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581131863,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581160807,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175700,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581245186,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249511,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270222,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305579,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581457590,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581522483,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581548622,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559903,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627050,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581643941,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722745,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581969710,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071581992337,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582076983,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582114972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115873,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582258695,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264921,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582299019,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582307647,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582315548,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316869,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318022,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582396903,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582397417,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437637,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582468088,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
      "addr": 18446744071582848494,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036251,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044107,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583053032,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058471,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154476,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313331,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583390256,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396617,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583447358,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583465694,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584444217,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786387,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585184086,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442070,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515788,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585652072,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586494140,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_copy_from_slot",
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
      "addr": 18446744071586496972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586563534,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586937149,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071588272282,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:66",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580060780,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255081,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697517,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071580774456,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580822598,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868397,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581012170,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581080855,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099384,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581126783,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581200370,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581247160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581286184,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309472,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581376814,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382979,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409332,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445222,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581599635,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581664749,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581693025,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703882,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771469,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581789675,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868797,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582118942,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582141876,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582227922,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582263996,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265772,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407737,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414118,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448056,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582456815,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464819,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466218,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467398,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582547627,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582548351,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588234,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582619645,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071583005358,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201646,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209499,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583218712,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224635,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329738,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data",
        "block/bio.c:bio_copy_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496343,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569676,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576086,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583627486,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583646667,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
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
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584853850,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206617,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587277,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585612775,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585873030,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947578,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084362,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586962010,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
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
      "addr": 18446744071586964933,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587031072,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430502,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071588828042,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579812517,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580118269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580315522,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829884,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071580910800,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959228,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004744,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581145802,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581219867,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243528,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581269254,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345694,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581346592,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391347,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581415707,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448201,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581526225,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533036,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565039,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604374,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581756677,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581828059,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581859885,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871228,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943905,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071581963581,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051417,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582307586,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582330898,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582417702,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598059,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604739,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637780,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582646700,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582655850,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657922,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658390,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738989,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582740436,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780803,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071582811113,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
      "addr": 18446744071583206014,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410126,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418503,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583426857,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432615,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538948,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710311,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785423,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583792238,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843774,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583864831,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
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
      "addr": 18446744071585084938,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442777,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831717,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585858962,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118955,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194756,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/scsi/sd_dif.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd_dif.c:sd_dif_complete",
        "drivers/scsi/sd_dif.c:sd_dif_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331978,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587256924,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:bitmap_copy_from_slot",
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
      "addr": 18446744071587260601,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_remap_zone_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587329164,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587733747,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589206229,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:67",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579859269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580164957,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368098,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813387,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899095,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580985543,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035452,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581080570,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581225626,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581303579,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327029,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581352566,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581429790,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581430688,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474809,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581499070,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531076,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581608561,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618949,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651696,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689814,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581843157,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581915307,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581944665,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956318,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029582,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582045962,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582139357,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582406290,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582429503,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582517161,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551713,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553009,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699771,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706457,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739524,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582748461,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757706,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759823,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760278,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582842749,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582844196,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884067,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582914064,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582948827,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322958,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531838,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538935,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583548057,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554103,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661336,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818997,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865551,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583871104,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_complete",
        "block/t10-pi.c:t10_pi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927473,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583950849,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
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
      "addr": 18446744071585189141,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195657,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566361,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585965925,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585990495,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264459,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328991,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586473578,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587437663,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "drivers/md/md-bitmap.c:md_bitmap_print_sb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507500,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587867901,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589447829,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579893494,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580211059,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580420828,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902481,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996755,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581099378,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144172,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581299427,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581371545,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390035,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581438030,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581462989,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542524,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581543653,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589794,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581608673,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641829,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581720431,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731512,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768822,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808322,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967740,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582052457,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582080785,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089001,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169259,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582210340,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582303516,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582575061,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582598783,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582684634,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724005,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725508,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872499,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879748,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913320,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582924099,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931966,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934052,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934518,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017836,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583019330,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064608,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583093472,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583129423,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510475,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719809,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727021,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583737225,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743186,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848897,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009355,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055722,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584061909,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_complete",
        "block/t10-pi.c:t10_pi_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107364,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584129952,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
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
      "addr": 18446744071585405376,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408022,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785865,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209061,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586227288,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586508401,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579950,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586718531,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587709951,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071587781412,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588173391,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589905605,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579943766,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580259459,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580469580,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955663,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051165,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581156318,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201708,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581228053,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358195,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581431249,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450259,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581502254,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581527085,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607423,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581608549,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653458,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581679572,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712950,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581793887,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581804648,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880914,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582040828,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582137331,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582158225,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166431,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246651,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582291236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582322885,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402540,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582676021,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582699519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582786810,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826535,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828410,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969303,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582979043,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986237,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019896,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583030661,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038542,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040666,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041142,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583124028,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583125522,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174016,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583205095,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583235631,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616363,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829521,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836685,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583846985,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852978,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583951809,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071584112856,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178058,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584184160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230564,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584253146,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585542096,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548767,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929401,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357109,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586375512,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586656333,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586727295,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586865139,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587914255,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071587986116,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588378532,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071590131589,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579988357,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580329304,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553998,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118856,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581233940,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071581256310,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581342123,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388143,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
        "mm/shmem.c:shmem_undo_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415829,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555659,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627451,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581655869,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710286,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581735349,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822246,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071581823601,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871784,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071581931374,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582019519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:init_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024368,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062336,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582106740,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275554,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071582370403,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:block_write_full_page",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_writepage",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:cont_expand_zero",
        "fs/buffer.c:block_read_full_page",
        "fs/buffer.c:__block_write_begin_int",
        "fs/buffer.c:page_zero_new_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582395964,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402571,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483367,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071582574751,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612277,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582698111,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_do_writepage",
        "fs/iomap/buffered-io.c:iomap_write_end_inline",
        "fs/iomap/buffered-io.c:__iomap_write_begin",
        "fs/iomap/buffered-io.c:iomap_readpage_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987733,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071583011629,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071583099919,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138128,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140579,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583286199,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583287581,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303897,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337199,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071583348707,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356428,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583358636,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359016,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444162,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071583445714,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497737,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583523774,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071583563177,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583973367,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224955,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584235976,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584242811,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343420,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509055,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573731,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579361,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636094,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584646005,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:copy_page_to_iter",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135749,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264324,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268511,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663992,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135477,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163247,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587450078,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513199,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "addr": 18446744071587668684,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766354,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
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
      "caller_func": []
    },
    {
      "addr": 18446744071588838718,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250447,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:154",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589239056,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263366,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266537,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271002,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968033,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580314776,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542046,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151420,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581276560,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071581298358,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581379968,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431828,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071581458981,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600630,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071581673147,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704022,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758062,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581783593,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870262,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071581871482,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917928,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071581981891,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071582067967,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:init_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072906,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153044,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326741,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411392,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582414308,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582446504,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582454432,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582539950,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071582646269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684085,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763575,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583063397,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071583073268,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583178008,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583215296,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583221370,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401735,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403165,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419142,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454950,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071583465155,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583472716,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474787,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475144,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583556932,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071583558434,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606438,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632937,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071583675529,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584093208,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343339,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584354322,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361387,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584460662,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584619237,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690929,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584697249,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584755102,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584776227,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
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
      "addr": 18446744071585287029,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382836,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384959,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773896,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221333,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587247471,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587519918,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587579528,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "addr": 18446744071587729628,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786818,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
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
      "caller_func": []
    },
    {
      "addr": 18446744071588854894,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589064059,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249848,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:185",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589238448,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264486,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267991,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272397,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975629,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580318258,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545404,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292482,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071581315910,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581400880,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581451892,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071581479829,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623478,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071581718665,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725689,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784974,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581810856,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900870,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071581901986,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942801,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071582010937,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071582089227,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097909,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177031,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354661,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438192,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582441510,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582473306,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481488,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582568958,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071582676371,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714089,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796446,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088805,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071583098630,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583204634,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583242800,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583249225,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433667,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441309,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583477385,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071583487174,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494984,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497014,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497352,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583580184,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071583581871,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629685,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677474,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071583696537,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701678,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120568,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377851,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584388729,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395852,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584495527,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719091,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584725351,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584783566,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584822449,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071585070789,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170725,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267028,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269131,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586653944,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109349,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134773,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587401806,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463720,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "addr": 18446744071587608860,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672671,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
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
      "caller_func": []
    },
    {
      "addr": 18446744071588743826,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951164,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589144623,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:180",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589132240,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579305776,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309835,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314562,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106961,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580472006,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717052,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537394,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071581561164,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581651744,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706372,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071581734229,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071581890934,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy"
      ]
    },
    {
      "addr": 18446744071581991032,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996405,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582068750,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071582096754,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195560,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071582196674,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582246776,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_copy",
        "mm/migrate.c:migrate_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582313420,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071582401809,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409602,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_freepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413101,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675781,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760976,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582764428,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785648,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582794448,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582886238,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071582993776,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page",
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040713,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113644,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583428517,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071583438300,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583547904,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583584832,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583589584,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583782982,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790739,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583831705,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071583841630,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583849784,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851916,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852280,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583937270,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939887,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988643,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584036377,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071584056678,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584062337,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502070,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584773083,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584783961,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791084,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584902236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585213968,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585222058,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585517925,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624421,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777551,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780683,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200808,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682005,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587707992,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587973660,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041058,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "addr": 18446744071588197250,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_xfer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589350894,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
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
      "caller_func": []
    },
    {
      "addr": 18446744071589434290,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589660412,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589864447,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:191",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581847504,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589851888,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579360519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071579367272,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372761,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/dma/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580928745,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882993,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071581913025,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582108584,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115157,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582288686,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394739,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582507709,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071582537315,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582639157,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660577,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582917782,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926607,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019533,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:remove_arg_zero",
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583454054,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071583463751,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515641,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946673,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071584339044,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584353880,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584399383,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071584410313,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584418968,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421557,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421976,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584516982,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520617,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138994,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585457965,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585469286,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477443,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586051107,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586065690,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586670005,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586783637,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504856,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589050007,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589329343,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589575915,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824670,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "caller_func": []
    },
    {
      "addr": 18446744071590911987,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163324,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591393205,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071591376304,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581221393,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316113,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071582348097,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582588981,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781339,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_huge_page_from_user",
        "mm/memory.c:wp_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582901043,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583022797,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071583052748,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161173,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184241,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583466060,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043935,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071584055303,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573409,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071584988307,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005483,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585054183,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "addr": 18446744071585068362,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077616,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585186982,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191386,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863810,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216845,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586229238,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238563,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034707,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587058873,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589946200,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579175,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590895636,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591170363,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592512494,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
      "caller_func": []
    },
    {
      "addr": 18446744071592609814,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592885724,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593154661,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071595749378,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595949925,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:207",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581315825,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517269,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
      "addr": 18446744071582550972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582796341,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947512,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231965,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071583262867,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376821,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402001,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/page_poison.c:__kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686951,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281095,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216339,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231559,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585282247,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
      "addr": 18446744071585297706,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585307232,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416086,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420437,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095749,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587289859,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587315433,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590255464,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590920871,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591239156,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591529499,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592942945,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
      "caller_func": []
    },
    {
      "addr": 18446744071593040374,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593324332,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593606516,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071596273685,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581422069,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582686149,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
      "addr": 18446744071582721564,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583879800,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497895,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531530,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_read_folio",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585541296,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344853,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575731,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587595006,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596440,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264727,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_completion",
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591586404,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591876971,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591957105,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/gpu/drm/drm_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_cache.c:drm_clflush_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593692721,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
      "caller_func": []
    },
    {
      "addr": 18446744071593791886,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594081372,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594381108,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071597158421,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem-internal.h:210",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490338108,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "arch/arm64/kernel/probes/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490411552,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:__kvm_map_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491502016,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491744364,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492301192,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492408040,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336492534272,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492584248,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336492618528,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492761572,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336492833416,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492856760,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336492923628,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446603336492955968,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493047792,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493050632,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493103580,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493127304,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493159368,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493254772,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493269624,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493303356,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493351724,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493566728,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493682564,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493712040,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720592,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493817264,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336493867412,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493904172,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494002960,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494329012,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494356656,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494456620,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494497952,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494500868,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494645504,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494658468,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494671480,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494713292,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494726712,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494734468,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494736528,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494737160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494834156,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494835264,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494889544,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494918392,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336494958664,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495399492,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495640732,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495649252,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495660588,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495668760,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495771092,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336496042884,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496049208,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496105540,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496130944,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498203928,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498210676,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752388,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499203092,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499222120,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499553836,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499637580,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446603336499798824,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501145864,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446603336501231220,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501889812,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * kmap_atomic(struct page * page)
```

```json
{
  "name": "kmap_atomic",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224509260,
      "name": "kmap_atomic",
      "external": true,
      "loc": "arch/arm/mm/highmem.c:52",
      "file": "arch/arm/mm/highmem.c",
      "inline": "not declared, inlined",
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
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/pagewalk.c:walk_pgd_range",
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
        "mm/zswap.c:zswap_writeback_entry",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:calc_checksum",
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migration_entry_wait",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_compact",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:obj_free",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:obj_malloc",
        "mm/zsmalloc.c:zs_map_object",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
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
        "fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer",
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_do",
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
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_next",
        "crypto/skcipher.c:skcipher_walk_done",
        "crypto/ahash.c:hash_walk_next",
        "crypto/shash.c:shash_ahash_digest",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_truncate",
        "block/bio.c:zero_fill_bio_iter",
        "block/bounce.c:__blk_queue_bounce",
        "block/bounce.c:copy_to_high_bio_irq",
        "block/bio-integrity.c:bio_integrity_process",
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page",
        "lib/iov_iter.c:copy_page_to_iter_iovec",
        "drivers/char/virtio_console.c:pipe_to_sg",
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor",
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg",
        "drivers/scsi/sd.c:sd_init_command",
        "drivers/scsi/sd.c:sd_setup_write_same10_cmnd",
        "drivers/scsi/sd.c:sd_setup_write_same16_cmnd",
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector",
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
        "drivers/md/md-bitmap.c:md_bitmap_create",
        "drivers/md/md-bitmap.c:md_bitmap_daemon_work",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_init_from_disk",
        "drivers/md/md-bitmap.c:md_bitmap_file_clear_bit",
        "drivers/md/md-bitmap.c:md_bitmap_file_set_bit",
        "drivers/md/md-bitmap.c:md_bitmap_read_sb",
        "drivers/md/md-bitmap.c:md_bitmap_print_sb",
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error",
        "drivers/mmc/host/sdhci.c:sdhci_finish_data",
        "drivers/mmc/host/sdhci.c:sdhci_prepare_data",
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
      "addr": 3224509260,
      "name": "kmap_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284462296,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055284778172,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285537748,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285673272,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055285830048,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285903184,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055285935904,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286127168,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055286220380,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286248032,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055286327472,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 13835058055286368160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286487092,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055286488960,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286563816,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055286607000,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286656604,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055286783832,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286796488,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286845948,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286901888,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287141040,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055287285328,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055287317388,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287326312,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287436072,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055287497104,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287541392,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287651376,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288053096,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288086168,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288209996,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288263328,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288266148,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288457416,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288472660,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288484068,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288535332,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288549612,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288559628,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288562608,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288563060,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288680620,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288681884,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288751876,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288794776,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055288835280,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289428848,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289771912,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289782912,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289797824,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289807972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289945556,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055290273292,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290282424,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290352632,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290380996,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291915884,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292406508,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292849844,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292958576,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 13835058055293152972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294653144,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 13835058055294759856,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295298852,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272430674,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272585386,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272621212,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936272643766,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272742356,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936272787052,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272803906,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936272843670,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446743936272868726,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272917174,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936272918280,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272951304,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273012510,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022864,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273046384,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273078980,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273223850,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273305910,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273325496,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273332016,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273399574,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273431650,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273460440,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273516944,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273765280,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273785980,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936273864094,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896820,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273898760,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274013594,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274022876,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274030372,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274064552,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936274074300,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274081452,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083318,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083704,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274157568,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936274158272,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274204456,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274231390,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936274261026,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274599612,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274795358,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274803070,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274812534,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274819448,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274917952,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936275120558,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275127210,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275171678,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275189626,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:copy_page_from_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276256816,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276493586,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276753630,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276820304,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446743936276950700,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277858560,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446743936277925736,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278207732,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579911542,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580228259,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580438380,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924463,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020013,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581125166,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581170556,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581196901,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327043,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581400097,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419107,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581470990,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581495821,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576159,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581577285,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622194,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581648308,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681686,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581762623,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773384,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849650,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582009564,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582106067,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582126961,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135167,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215387,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582259972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582291621,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582371276,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582644757,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582668255,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582755546,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795271,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797146,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938039,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582947779,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954973,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988632,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582999397,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007278,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009402,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009878,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092764,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583094258,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142752,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583173831,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583204367,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585099,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583798257,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805421,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583815721,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821714,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920545,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071584081592,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146794,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584152896,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584199300,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584221882,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585304128,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310799,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690377,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118997,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137928,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346813,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417775,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586623667,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545231,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071587617092,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985316,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589733845,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579850774,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580175747,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580385452,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870522,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966109,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581072142,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117372,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581143653,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270803,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581342609,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361619,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581413246,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581438061,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517727,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581518853,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563490,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581591137,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620349,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581701247,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711787,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747636,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787314,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581947132,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582043507,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582064401,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072607,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152273,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582196897,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582229381,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308972,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582581925,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582605423,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582692714,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732423,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734298,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875191,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582884931,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892125,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925784,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582936549,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944430,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582946554,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947030,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029916,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583031410,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079904,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583110983,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583141519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522155,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735313,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742477,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583752777,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758770,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857505,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071584017352,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082330,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584088160,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584134516,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584157098,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585550073,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963621,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586100994,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:pmem_do_bvec",
        "drivers/nvdimm/pmem.c:write_pmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586107636,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586116150,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/nvdimm/blk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586188136,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294031,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586492179,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313327,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071587385108,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587698420,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071589459525,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579904038,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580219731,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580429628,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915711,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011213,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581116366,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161756,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581188101,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318243,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581391297,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410307,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581462302,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581487133,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567471,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581568597,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613506,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581639620,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672998,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581753935,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764696,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801284,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840962,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582000844,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582096547,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582117441,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125647,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205867,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582250452,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582282101,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361756,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582634613,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582658111,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582745402,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784151,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786026,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926647,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582936387,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943581,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582977240,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582988005,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995886,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998010,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998486,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583081372,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583082866,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126784,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583157863,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583188399,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568875,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782017,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789181,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583799481,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805474,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904305,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071584065352,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130554,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136656,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183060,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584205642,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585492496,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499167,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879625,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305077,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586323480,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586604301,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681855,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586819699,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587870399,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071587942260,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588317092,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071590177221,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
  "name": "kmap_atomic",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579950086,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580272523,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071580485224,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975775,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072428,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581178790,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227995,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581251365,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581382289,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581455200,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475394,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581523442,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581552800,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_writeback_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632415,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581633593,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:kernel_poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681237,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581706018,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740236,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071581825521,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833537,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870422,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910466,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582072044,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582169443,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582190408,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198639,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280108,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582330745,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582360661,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441452,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582717901,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582741778,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071582830650,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870519,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872436,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013716,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583023914,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031716,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583066032,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583077109,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085035,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086903,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087743,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_next_page",
        "fs/squashfs/page_actor.c:direct_first_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170700,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583172146,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220336,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583251528,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071583282894,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666011,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583883016,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890196,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/blkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_next",
        "crypto/blkcipher.c:blkcipher_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583900488,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:hash_walk_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906525,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005218,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071584168167,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234602,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584240752,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287462,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584310170,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_to_iter",
        "lib/iov_iter.c:csum_and_copy_from_iter_full",
        "lib/iov_iter.c:csum_and_copy_from_iter",
        "lib/iov_iter.c:iov_iter_copy_from_user_atomic",
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600496,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607199,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988825,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586416533,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435055,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_copy_from_grant",
        "drivers/block/xen-blkfront.c:blkif_queue_rw_req",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant",
        "drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586716605,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787871,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
      "addr": 18446744071586925811,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_sff_hsm_move",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985487,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_copy_from_slot",
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
      "addr": 18446744071588057547,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452396,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071590227669,
      "name": "kmap_atomic",
      "external": false,
      "loc": "include/linux/highmem.h:91",
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void * kmap_atomic(struct page * page)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void * kmap_atomic(struct page * page)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * kmap_atomic(struct page * page)
```
</details>
</li>
</ul>
