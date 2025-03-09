# Function: <code>__percpu_counter_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __percpu_counter_add(struct percpu_counter * fbc, s64 amount, s32 batch)
```

```json
{
  "name": "__percpu_counter_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583112000,
      "name": "__percpu_counter_add",
      "external": true,
      "loc": "lib/percpu_counter.c:75",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:wb_writeout_inc",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/mmap.c:__vm_enough_memory",
        "mm/mmap.c:__vm_enough_memory",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:exit_mmap",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:move_vma",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink",
        "fs/file_table.c:get_empty_filp",
        "fs/file_table.c:get_empty_filp",
        "fs/file_table.c:__fput",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_claim_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/extents_status.c:ext4_es_free_extent",
        "fs/ext4/extents_status.c:ext4_es_free_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_group_served",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "lib/flex_proportions.c:fprop_new_period",
        "lib/flex_proportions.c:__fprop_inc_single",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "net/core/sock.c:sk_clone_lock",
        "net/core/sock.c:sk_clone_lock",
        "net/core/dst.c:dst_init",
        "net/core/dst.c:dst_destroy",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583112000,
      "name": "__percpu_counter_add",
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
void __percpu_counter_add(struct percpu_counter * fbc, s64 amount, s32 batch)
```

```json
{
  "name": "__percpu_counter_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406256,
      "name": "__percpu_counter_add",
      "external": true,
      "loc": "lib/percpu_counter.c:75",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink",
        "fs/file_table.c:__fput",
        "fs/file_table.c:get_empty_filp",
        "fs/file_table.c:get_empty_filp",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/balloc.c:ext4_claim_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_group_served",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_single",
        "lib/flex_proportions.c:fprop_new_period",
        "net/core/sock.c:sk_clone_lock",
        "net/core/dst.c:dst_destroy",
        "net/core/dst.c:dst_init",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406256,
      "name": "__percpu_counter_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void __percpu_counter_add(struct percpu_counter * fbc, s64 amount, s32 batch)
```

```json
{
  "name": "__percpu_counter_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531632,
      "name": "__percpu_counter_add",
      "external": true,
      "loc": "lib/percpu_counter.c:75",
      "file": "lib/percpu_counter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:wb_writeout_inc",
        "mm/shmem.c:__shmem_file_setup",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_alloc_and_acct_page",
        "mm/shmem.c:shmem_evict_inode",
        "mm/shmem.c:shmem_setattr",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_uncharge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_charge",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/shmem.c:shmem_recalc_inode",
        "mm/util.c:__vm_enough_memory",
        "mm/util.c:__vm_enough_memory",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_brk",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:mmap_region",
        "mm/mprotect.c:mprotect_fixup",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:SyS_mremap",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:SyS_swapoff",
        "mm/frontswap.c:frontswap_shrink",
        "fs/file_table.c:__fput",
        "fs/file_table.c:get_empty_filp",
        "fs/file_table.c:get_empty_filp",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dquot_disable",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqget",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dqcache_shrink_scan",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_writeback_dquots",
        "fs/quota/dquot.c:dquot_scan_active",
        "fs/ext4/balloc.c:ext4_claim_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_new_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_generate_buddy",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepages_fill",
        "fs/fuse/file.c:fuse_writepage_locked",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/blk-core.c:generic_make_request_checks",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_completed_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_insert_request",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_merged_requests",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_bio_merged",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_remove_request",
        "block/cfq-iosched.c:cfq_group_served",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "lib/flex_proportions.c:__fprop_inc_percpu_max",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_percpu",
        "lib/flex_proportions.c:__fprop_inc_single",
        "lib/flex_proportions.c:fprop_new_period",
        "net/core/sock.c:sk_clone_lock",
        "net/core/dst.c:dst_destroy",
        "net/core/dst.c:dst_init",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close",
        "net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_init_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/inet_fragment.c:inet_frag_find",
        "net/ipv4/inet_fragment.c:inet_frag_destroy",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531632,
      "name": "__percpu_counter_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __percpu_counter_add(struct percpu_counter * fbc, s64 amount, s32 batch)
```
</details>
</li>
</ul>
