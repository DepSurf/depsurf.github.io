# Function: <code>put_zone_device_private_or_public_page</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void put_zone_device_private_or_public_page(struct page * page)
```

```json
{
  "name": "put_zone_device_private_or_public_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580717696,
      "name": "put_zone_device_private_or_public_page",
      "external": true,
      "loc": "kernel/memremap.c:508",
      "file": "kernel/memremap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "kernel/exit.c:do_exit",
        "kernel/power/swap.c:hib_end_io",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/futex.c:get_futex_key",
        "kernel/events/core.c:perf_prepare_sample",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "kernel/memremap.c:devm_memremap_pages_release",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:find_get_entry",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:filemap_range_has_page",
        "mm/page-writeback.c:write_one_page",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/readahead.c:read_cache_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:put_pages_list",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:putback_lru_page",
        "mm/vmscan.c:putback_lru_page",
        "mm/shmem.c:shmem_get_link",
        "mm/shmem.c:shmem_put_link",
        "mm/shmem.c:shmem_symlink",
        "mm/shmem.c:shmem_fallocate",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_write_end",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_writepage",
        "mm/shmem.c:shmem_unuse",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/shmem.c:shmem_unused_huge_shrink",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:undo_dev_pagemap",
        "mm/gup.c:get_user_pages_longterm",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/mincore.c:mincore_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:free_page_and_swap_cache",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:free_swap_and_cache",
        "mm/swapfile.c:scan_swap_map_slots",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/zswap.c:zswap_writeback_entry",
        "mm/hugetlb.c:putback_active_hugepage",
        "mm/hugetlb.c:huge_pmd_unshare",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_acct_memory",
        "mm/hugetlb.c:prep_new_huge_page",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:stable_node_dup",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:remove_stable_node",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:get_ksm_page",
        "mm/ksm.c:break_ksm",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:isolate_movable_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:unpoison_memory",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:me_huge_page",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:__free_zspage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/page_idle.c:page_idle_bitmap_write",
        "mm/page_idle.c:page_idle_bitmap_read",
        "mm/page_idle.c:page_idle_get_page",
        "mm/frame_vector.c:put_vaddr_frames",
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/read_write.c:vfs_dedupe_file_range_compare",
        "fs/pipe.c:generic_pipe_buf_release",
        "fs/pipe.c:anon_pipe_buf_release",
        "fs/namei.c:page_put_link",
        "fs/namei.c:page_get_link",
        "fs/libfs.c:simple_write_end",
        "fs/splice.c:iter_to_pipe",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:page_cache_pipe_buf_release",
        "fs/buffer.c:block_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_truncate_page",
        "fs/buffer.c:nobh_write_end",
        "fs/buffer.c:nobh_write_begin",
        "fs/buffer.c:generic_write_end",
        "fs/buffer.c:block_write_begin",
        "fs/buffer.c:__getblk_gfp",
        "fs/block_dev.c:blkdev_write_end",
        "fs/block_dev.c:blkdev_bio_end_io",
        "fs/block_dev.c:__blkdev_direct_IO_simple",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:dio_bio_complete",
        "fs/mpage.c:mpage_readpages",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_migratepage",
        "fs/aio.c:aio_free_ring",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/iomap.c:iomap_dio_bio_end_io",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/iomap.c:iomap_dirty_actor",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_end",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_block_zero_page_range",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_writepage",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_mb_release_context",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/mballoc.c:ext4_mb_init_group",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/ext4/symlink.c:ext4_encrypted_get_link",
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/squashfs/file_direct.c:squashfs_readpage_block",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:hugetlbfs_fallocate",
        "fs/hugetlbfs/inode.c:remove_inode_hugepages",
        "fs/hugetlbfs/inode.c:hugetlbfs_read_iter",
        "fs/ecryptfs/mmap.c:ecryptfs_write_end",
        "fs/ecryptfs/mmap.c:ecryptfs_write_begin",
        "fs/ecryptfs/read_write.c:ecryptfs_write",
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_dev_splice_read",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_finish",
        "fs/fuse/file.c:fuse_write_end",
        "fs/fuse/file.c:fuse_write_begin",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_perform_write",
        "fs/fuse/file.c:fuse_readpages_end",
        "fs/fuse/file.c:fuse_release_user_pages",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "block/bio.c:bio_check_pages_dirty",
        "block/bio.c:bio_dirty_fn",
        "block/bio.c:bio_unmap_user",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/bio.c:bio_map_user_iov",
        "block/partition-generic.c:read_dev_sector",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:read_lba",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/scsi/scsicam.c:scsi_bios_ptable",
        "drivers/net/tun.c:tun_get_user",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:read_rdev",
        "drivers/md/md.c:md_rdev_clear",
        "drivers/md/md.c:md_rdev_clear",
        "net/core/sock.c:__sk_destruct",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:sock_spd_release",
        "net/core/skbuff.c:__pskb_pull_tail",
        "net/core/skbuff.c:___pskb_trim",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_copy_ubufs",
        "net/core/skbuff.c:skb_release_data",
        "net/core/dev.c:gro_pull_from_frag0",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:__pskb_trim_head"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580717696,
      "name": "put_zone_device_private_or_public_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void put_zone_device_private_or_public_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void put_zone_device_private_or_public_page(struct page * page)
```
</details>
</li>
</ul>
