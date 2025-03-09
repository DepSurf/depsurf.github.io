# Function: <code>pagefault_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pagefault_enable()
```

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578963019,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100938,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328421,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893767,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:futex_wake_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579945069,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219103,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580316898,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580446788,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:copy_from_page",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_notify_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580489024,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:strncpy_from_unsafe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580508368,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545621,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread",
        "mm/vmalloc.c:vwrite"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760060,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020595,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581035264,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:__page_symlink"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158271,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260975,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820990,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861143,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901522,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049040,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640421,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582650781,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582661886,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_compat_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716511,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582938789,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004917,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583015466,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021302,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "addr": 18446744071583851871,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183882,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584535812,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584872491,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "addr": 18446744071585773632,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:bitmap_file_clear_bit",
        "drivers/md/bitmap.c:bitmap_file_set_bit",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_init_from_disk",
        "drivers/md/bitmap.c:bitmap_daemon_work",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_copy_from_slot"
      ],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_print_sb",
        "drivers/md/bitmap.c:bitmap_create"
      ]
    },
    {
      "addr": 18446744071586211571,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
  "symbols": [
    {
      "addr": 18446744071585773632,
      "name": "pagefault_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pagefault_enable()
```

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876270,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100498,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333852,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579926554,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579975903,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580255919,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:tracing_mark_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580371609,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529708,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580573367,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590321,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634792,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vwrite",
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580882507,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179043,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581323389,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426703,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581754566,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016732,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060445,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088684,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142137,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264139,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582889671,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897750,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582908346,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582993448,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583226143,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583295383,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583306377,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318648,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584181389,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523004,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584887495,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919942,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585235518,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/ata/libata-sff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586188073,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
        "drivers/md/bitmap.c:bitmap_file_set_bit"
      ],
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_create",
        "drivers/md/bitmap.c:bitmap_print_sb"
      ]
    },
    {
      "addr": 18446744071586635500,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
  "symbols": [
    {
      "addr": 18446744071586171248,
      "name": "pagefault_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void pagefault_enable()
```

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578876350,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579098802,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349132,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/power/snapshot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579957258,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006413,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580419353,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593696,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580639799,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657195,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701897,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222548,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581402563,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507916,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581842802,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106780,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582150258,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178772,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231827,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353787,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986246,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582994208,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/skcipher.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583003302,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583008068,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098403,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583332084,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414135,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583425577,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583442028,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "lib/swiotlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584362753,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705083,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585088421,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585103297,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585431006,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
      "file": "drivers/ata/libata-sff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586392217,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
      "caller_func": [
        "drivers/md/bitmap.c:bitmap_create"
      ]
    },
    {
      "addr": 18446744071586820908,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:35",
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
  "symbols": [
    {
      "addr": 18446744071586374976,
      "name": "pagefault_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875690,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090735,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342954,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579962373,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013934,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430353,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580623494,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580672334,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689902,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580735897,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270391,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581457655,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581559990,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581969770,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115061,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115889,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265155,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316886,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437845,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036273,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044177,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583053324,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583058528,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154771,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583390451,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583446075,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465854,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584444282,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786480,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585160429,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585515800,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586935824,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
      "addr": 18446744071588271332,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272331,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:195",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578876784,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579102034,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368445,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580014127,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580486777,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580704409,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757526,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774502,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580822663,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581409429,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581599700,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703969,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582119002,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264085,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265864,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414190,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466074,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588305,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201748,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209569,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583219101,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224692,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329827,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583569754,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583626059,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583646739,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "lib/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584853896,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206710,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585587437,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947692,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587428880,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "addr": 18446744071588827076,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588828091,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878374,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107616,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381017,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812560,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580071103,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:do_futex",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580118351,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574105,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580836885,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893595,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910846,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959295,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565141,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604435,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581756745,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871315,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582051491,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582307645,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452321,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582453603,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582604807,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582657995,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658460,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780874,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583410228,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418744,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583427172,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432672,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539030,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583785502,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "block/blk-zoned.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-zoned.c:blkdev_report_zones"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583842139,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583864915,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442870,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585831886,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194870,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587733964,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
      "addr": 18446744071589205171,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589206283,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:196",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878086,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113184,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:save_stack_trace_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408585,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:mpx_notify_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579859312,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580110775,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165039,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580813471,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905317,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968235,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580985589,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:get_page_from_freelist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035519,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651802,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581843225,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581956405,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582139418,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551798,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553093,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706525,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759948,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760348,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884138,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323071,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531940,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583539176,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583548431,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554160,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583661418,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865630,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583950951,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195703,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566454,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585966094,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586329037,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868124,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071589446755,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589447883,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578878839,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/core.c:perf_callchain_user32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579104023,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579122656,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422175,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893528,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580148696,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580211141,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902563,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581004001,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063822,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099443,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768916,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967808,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089088,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582303576,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724090,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725590,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879807,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934178,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582934592,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064669,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510587,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719908,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727280,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583737606,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743242,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583848604,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055791,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130061,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585408060,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785954,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209224,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579996,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588172128,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071589904660,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589905662,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879375,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105689,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124528,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425343,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579943800,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580196712,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259541,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955745,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057993,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119790,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581156383,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841330,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582040896,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166518,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582322946,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402600,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582826620,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582828502,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582979153,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986296,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583040792,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583041216,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174077,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583616475,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829620,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836944,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583847366,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583853034,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583951516,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584178127,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584253255,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585548805,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929490,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357272,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586727341,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377328,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071590130644,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131646,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883618,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user",
        "arch/x86/events/core.c:perf_callchain_user32"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118821,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139462,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579988391,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580264939,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580329386,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_page",
        "kernel/kexec_core.c:kimage_alloc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554067,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581118942,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581146717,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256454,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581303852,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342188,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388180,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581415911,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555705,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581627531,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581655915,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710405,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581735427,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581822326,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581823608,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/page_poison.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_poison.c:kernel_poison_pages",
        "mm/page_poison.c:poison_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071581931425,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071582019710,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:init_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024430,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062430,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582106624,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275622,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071582370484,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071582396034,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402658,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mpage.c:__mpage_writepage",
        "fs/mpage.c:do_mpage_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582483409,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071582574797,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612338,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582698214,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071582987792,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071583011703,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071583100026,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138213,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140664,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583286077,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583287672,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303956,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/jbd2/commit.c:jbd2_block_tag_csum_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337255,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071583348791,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file.c:squashfs_readpage",
        "fs/squashfs/file.c:squashfs_fill_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356352,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583358711,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583359088,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/page_actor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/page_actor.c:direct_finish_page",
        "fs/squashfs/page_actor.c:direct_next_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583444246,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071583445816,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497799,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583523933,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071583563246,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583973458,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225054,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584236284,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584242867,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343144,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_copy_data_iter",
        "block/bio.c:bio_copy_data_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509105,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573798,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bio-integrity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio-integrity.c:bio_integrity_process",
        "block/bio-integrity.c:bio_integrity_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579446,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/t10-pi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/t10-pi.c:t10_pi_type1_complete",
        "block/t10-pi.c:t10_pi_type1_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635858,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584646096,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
        "lib/iov_iter.c:memcpy_mcsafe_to_page",
        "lib/iov_iter.c:csum_and_copy_to_pipe_iter",
        "lib/iov_iter.c:memzero_page",
        "lib/iov_iter.c:memcpy_to_page",
        "lib/iov_iter.c:memcpy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585134869,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585135806,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586264362,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268549,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664084,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587135646,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:transfer_xor",
        "drivers/block/loop.c:transfer_xor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587163313,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071587447765,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587513245,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071587668743,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes",
        "drivers/ata/libata-sff.c:ata_pio_sector"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588766404,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071588838783,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589243504,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879698,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118717,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136572,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579263637,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271140,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398912,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579968076,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580251628,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314858,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151508,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581186765,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275449,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:is_trap_at_addr",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581346767,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380028,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581431866,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704068,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758181,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:__zs_map_object",
        "mm/zsmalloc.c:init_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072968,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152928,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326791,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411486,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582414438,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582446557,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582454496,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582539992,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582684146,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763631,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end_inline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583063456,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583178061,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583215360,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583221495,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401613,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403256,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583419201,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475216,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606500,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584093307,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343438,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584354677,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584361443,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584460388,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584690990,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584776324,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "addr": 18446744071585286213,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287086,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382874,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586384997,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586773988,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587221502,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587579574,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589064216,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242800,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578882183,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125337,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143638,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264748,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272527,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402032,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579975667,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580256828,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_owner",
        "kernel/futex.c:attach_to_pi_state",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580318340,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204861,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300799,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581365743,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400943,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581451930,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725735,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_pcp_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785093,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097968,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177117,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354711,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438286,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582441641,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582473359,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582481555,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582569000,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796510,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_end"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088864,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583204687,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583242867,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583249350,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433781,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441368,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497139,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497424,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629747,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701833,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120667,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584377947,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584389029,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395909,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584495254,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584822538,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585169973,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585170782,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586267066,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586269169,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654036,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109512,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463766,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588951319,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589137776,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:254",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578886007,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149877,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170758,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579306165,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314701,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579464368,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580106996,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_or_poison_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580408108,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wait_setup",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:futex_lock_pi_atomic",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472086,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444933,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581536476,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581614127,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651866,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581706410,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996442,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582068869,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:alloc_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409648,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/secretmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/secretmem.c:secretmem_freepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582413161,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494605,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_string_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675831,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/libfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/libfs.c:simple_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582761070,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582764594,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582785778,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582794573,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/mpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582886280,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113810,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583428576,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583548034,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583584957,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583589709,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ext4/readpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583783096,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583790798,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583851990,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583852352,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939989,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988703,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_add_dirent_to_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584062499,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "fs/fuse/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/ioctl.c:fuse_do_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502169,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584773179,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584784261,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584791141,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584902410,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585212701,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585222401,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585623669,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624478,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586777589,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586780721,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200900,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587682168,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041104,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_ce_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589660567,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589856864,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:244",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578883790,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191924,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216642,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360931,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372943,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_encl_ewb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540969,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580627299,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_get_value_locked",
        "kernel/futex/core.c:futex_cmpxchg_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641117,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928831,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581784870,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581885901,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913100,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581974767,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108650,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115253,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582507863,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582660698,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019597,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515707,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946740,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584353952,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584421635,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584422156,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520733,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585139101,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585458065,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585471812,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477500,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586051252,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586066011,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782746,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586783701,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "arch/x86/lib/usercopy_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy_64.c:memcpy_page_flushcache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504953,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589050075,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589575987,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590824727,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
      "addr": 18446744071590912065,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591163500,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591386940,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:204",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578889071,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248069,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579273426,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579644857,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580893283,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_get_value_locked",
        "kernel/futex/core.c:futex_cmpxchg_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907693,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221479,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224613,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318762,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348172,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582409535,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582582402,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589077,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583022951,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184453,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "addr": 18446744071583483708,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043984,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584573476,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585005555,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187077,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191504,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863940,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586216945,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586232180,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238620,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587034868,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587059067,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590579243,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591170435,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592512551,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592885900,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593150556,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595949117,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595949989,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:213",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578887046,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254930,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279803,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658969,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580977139,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_get_value_locked",
        "kernel/futex/core.c:futex_cmpxchg_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992317,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315911,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743886,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426856,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519939,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582551059,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582615519,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789589,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796437,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/util.c:memcmp_pages",
        "mm/util.c:memcmp_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997852,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_folio_from_user",
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232119,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:calc_checksum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402213,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "addr": 18446744071583700042,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281149,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216431,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_freeze_jh_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585231631,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585416181,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/ecryptfs/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420559,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095879,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587290020,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587315617,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590920939,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591529571,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592943002,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593324508,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593604092,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596466538,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578909350,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284906,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309707,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579692889,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581070979,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:futex_get_value_locked",
        "kernel/futex/core.c:futex_cmpxchg_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087293,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/futex/waitwake.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/waitwake.c:futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422155,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581860702,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_event_perf",
        "kernel/trace/trace_events_user.c:user_event_ftrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593144,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688819,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721651,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582787039,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:strncpy_from_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault",
        "mm/maccess.c:copy_to_kernel_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964509,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177273,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:copy_folio_from_user",
        "mm/memory.c:__wp_page_copy_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583879892,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "addr": 18446744071583894493,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584497949,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault_cow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585531621,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344983,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587575892,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587595183,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:copy_page_from_iter_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596537,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591264795,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591877043,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:__atapi_pio_bytes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591957174,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/gpu/drm/drm_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_cache.c:drm_clflush_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593692781,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_mc_scrub_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594081548,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "drivers/firmware/efi/capsule.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/capsule.c:efi_capsule_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594378684,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "lib/buildid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/buildid.c:build_id_parse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597361562,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:235",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490300940,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/arm64/kernel/perf_callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/perf_callchain.c:perf_callchain_user",
        "arch/arm64/kernel/perf_callchain.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490338184,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/arm64/kernel/probes/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/probes/uprobes.c:arch_uprobe_copy_ixol"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490409600,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:__kvm_read_guest_atomic",
        "virt/kvm/kvm_main.c:__kvm_unmap_gfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491447948,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491502084,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492301296,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492352696,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492407144,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:is_trap_at_addr",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492490704,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492534344,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493303460,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493351784,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493566800,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493720668,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493904228,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494003016,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494498012,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494500944,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494658560,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494671536,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494736592,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494737272,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494889584,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495399564,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495640788,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495649492,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495661040,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495668816,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495771148,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496131052,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498210708,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752468,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499203240,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499637628,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501888848,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224468752,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/arm/kernel/perf_callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/perf_callchain.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 3224509056,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/arm/mm/highmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/highmem.c:__kunmap_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3225421080,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3226266588,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 3226300420,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp"
      ],
      "caller_func": []
    },
    {
      "addr": 3226362088,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282354228,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/traps.c:handle_hmi_exception"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282715664,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282901380,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/lib/vmx-helper.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/lib/vmx-helper.c:exit_vmx_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283364316,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/perf/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/callchain.c:read_user_stack_32",
        "arch/powerpc/perf/callchain.c:read_user_stack_32",
        "arch/powerpc/perf/callchain.c:read_user_stack_64",
        "arch/powerpc/perf/callchain.c:read_user_stack_64"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283380432,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/powerpc/perf/core-book3s.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/core-book3s.c:record_and_restart",
        "arch/powerpc/perf/core-book3s.c:record_and_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284378388,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_atomic_op_inuser",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284462372,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285537844,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285581980,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285683456,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285776316,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285830124,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286846080,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287141148,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287326392,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287541456,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287651444,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288263396,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288266224,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288472776,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288484136,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288562676,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288563156,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288751948,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289428928,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289771992,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289783172,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289798432,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289808032,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289945648,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290381068,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292406700,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292958728,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295296836,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271903410,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_wake_op",
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272430820,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272493010,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272552664,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272585408,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
        "mm/zsmalloc.c:zs_unmap_object",
        "mm/zsmalloc.c:zs_map_object",
        "mm/zsmalloc.c:zs_map_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273022916,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273046758,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273223872,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273332078,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273460502,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273516996,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273896884,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273898792,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:pagecache_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274022958,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274030648,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083372,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274083792,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274204774,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274599688,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274795526,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274803280,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274812938,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274819506,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274918228,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275189876,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276493730,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276820362,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278206342,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879375,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106073,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124912,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421183,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579911576,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580165512,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580228341,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924545,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026841,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088638,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125231,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810066,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582009632,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135254,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582291682,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582371336,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582795356,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582797238,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582947889,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582955032,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009528,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583009952,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583142813,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585211,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583798356,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805680,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583816102,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583821770,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920252,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584146863,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584221991,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310837,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690466,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586119160,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417821,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587984112,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071589732900,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589733902,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873215,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038489,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056848,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350319,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579850808,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580113128,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175829,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870604,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580972937,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035822,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072207,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747730,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581947200,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072694,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582229442,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309032,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732508,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734390,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582885041,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892184,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582946680,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947104,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079965,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522267,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583735412,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583742736,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583753158,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758826,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583857212,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082399,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584157207,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585963784,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/nvdimm/blk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586182837,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294077,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587697216,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071589458580,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459582,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879311,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579105625,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579124464,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579421103,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579904072,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580156984,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580219813,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915793,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018041,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079838,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116431,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581801378,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582000912,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582125734,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582282162,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361816,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784236,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582786118,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582936497,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943640,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998136,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998560,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126845,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568987,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583782116,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789440,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583799862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583805530,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904012,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130623,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584205751,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585499205,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879714,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586305240,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681901,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588315888,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071590176276,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590177278,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
  "name": "pagefault_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578879663,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:perf_callchain_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110504,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/fpu/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129584,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/stacktrace.c:arch_stack_walk_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430175,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/mm/mpx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mpx.c:mpx_unmap_tables",
        "arch/x86/mm/mpx.c:mpx_unmap_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950127,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/power/snapshot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/snapshot.c:clear_free_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/dma/swiotlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580209000,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_value_locked",
        "kernel/futex.c:cmpxchg_futex_value_locked",
        "kernel/futex.c:arch_futex_atomic_op_inuser"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272612,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_support.c:kdb_getphys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975864,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079353,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:__update_ref_ctr",
        "kernel/events/uprobes.c:copy_to_page",
        "kernel/events/uprobes.c:copy_from_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141726,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178862,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870554,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582072119,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198733,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582360729,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/verity/verify.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/verify.c:extract_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441519,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/move_extent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:mext_page_mkuptodate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870611,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_bio_write_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582872518,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583024028,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:do_get_write_access"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031784,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/symlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583086996,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/squashfs/file_direct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087628,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220404,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "fs/fuse/readdir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/readdir.c:fuse_emit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583666130,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583883119,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/scatterwalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/scatterwalk.c:scatterwalk_copychunks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890472,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/skcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583900893,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/ahash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ahash.c:crypto_hash_walk_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906581,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "crypto/shash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/shash.c:shash_ahash_digest"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584004893,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "block/bounce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bounce.c:__blk_queue_bounce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234678,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "lib/scatterlist.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/scatterlist.c:sg_miter_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584310286,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_dma_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607244,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/xen/balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/balloon.c:decrease_reservation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988921,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586416710,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_kunmap_atomic_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586787924,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "drivers/edac/edac_mc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_mc.c:edac_raw_mc_handle_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588451884,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
      "addr": 18446744071590226724,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
      "file": "arch/x86/lib/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/usercopy.c:copy_from_user_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590227733,
      "name": "pagefault_enable",
      "external": false,
      "loc": "include/linux/uaccess.h:193",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void pagefault_enable()
```
</details>
</li>
</ul>
