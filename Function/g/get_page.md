# Function: <code>get_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579309335,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579892854,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:get_futex_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580141229,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580391112,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580448710,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580474673,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521512,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580538513,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:get_kernel_pages",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:lru_add_page_tail"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559678,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585322,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580659691,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580672216,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580691846,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec",
        "mm/mlock.c:munlock_vma_pages_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697473,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580755747,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580763543,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580802147,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833777,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880141,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900932,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919875,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580948267,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027037,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219070,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245453,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316753,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576331,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786081,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905261,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051017,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582083879,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582296727,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583020672,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc"
      ],
      "caller_func": [
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages_alloc"
      ]
    },
    {
      "addr": 18446744071583512235,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583840220,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584183610,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584208859,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584884957,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585082688,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585120870,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585773871,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218015,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567704,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586616061,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586995397,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587264196,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:487",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020672,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861841,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309555,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175356,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580458833,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523974,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580552754,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613947,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630540,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580651298,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580693780,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768436,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791849,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807841,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811892,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871843,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877721,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886029,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580933991,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938091,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961807,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021016,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041777,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052204,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581065219,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581120023,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186184,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383202,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421716,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487409,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497973,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764298,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981816,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091804,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265034,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300199,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582516696,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583312266,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583833167,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584169615,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523103,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584548251,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246957,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585474973,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585513928,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586171479,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586639872,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587007173,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587064600,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442118,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587729339,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:761",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861579,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324772,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215932,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580521282,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587299,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617266,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580681211,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580697756,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718434,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580759431,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833972,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580856185,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872885,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877252,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939731,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945737,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__add_to_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954120,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002313,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009834,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035769,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095616,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116942,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581123869,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140445,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581195131,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263400,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581461346,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501889,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569857,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582099,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:grab_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666208,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853358,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072056,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181904,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354662,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582388535,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582609497,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432808,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583972415,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584350911,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584705182,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730203,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446759,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585701853,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586375207,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586825456,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587202736,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587261116,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587645530,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587944150,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:750",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861008,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580225862,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554121,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617280,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580647241,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714419,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731622,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753980,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580794140,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872087,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901471,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917483,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921266,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984297,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999338,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049841,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057250,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083357,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142384,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164836,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175227,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187507,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581240098,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312188,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518414,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556036,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626410,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720496,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582001149,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034107,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268404,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437947,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472027,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582700563,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468320,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584020887,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432410,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786205,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584812331,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585529637,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782018,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586477463,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "drivers/md/bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586960443,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335254,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587389501,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587790974,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588097109,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:798",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578861600,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277062,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634889,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698033,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730889,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580799967,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817670,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841180,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883764,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580963479,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998857,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016891,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020870,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087317,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110555,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160751,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581194842,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254363,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293589,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299897,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318823,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581371664,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581452220,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659041,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699803,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772995,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866170,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151053,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582184347,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417479,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582589039,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582623979,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856403,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649232,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584236823,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584840538,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585206435,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585233099,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585961269,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586183562,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586220386,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586945063,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587452941,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587859652,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587905722,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588324546,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588641673,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:837",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863344,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580338358,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743812,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendpage",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761438,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830415,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865500,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935478,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954606,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977787,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581016101,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098394,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132649,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151898,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155755,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230160,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246509,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303923,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339902,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400575,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440696,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447596,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464762,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581523092,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611576,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581824115,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866850,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940753,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048210,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345803,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582375279,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608085,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781587,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817035,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583054691,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850362,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584457335,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071262,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585442595,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585469387,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209533,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435126,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586477730,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587240407,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587722274,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_alloc_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587756944,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_append_datato_frags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588203869,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588257244,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588681834,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589001265,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:917",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863392,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394966,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828254,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897669,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936359,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012422,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581030798,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054747,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098450,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178122,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214321,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231723,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235547,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313142,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330030,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387587,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423833,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484204,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524120,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532323,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548506,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581611476,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697928,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/pipe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/pipe.c:generic_pipe_buf_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911427,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581951895,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_blockdev_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582028481,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136095,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444769,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582475023,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709840,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884853,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918584,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583168515,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583934349,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584553863,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585179262,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585566179,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585592731,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586229731,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586350141,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577858,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586625436,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587421160,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587891201,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588124353,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588178302,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390329,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588445448,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588771672,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588897220,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589227910,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:968",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864014,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447782,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922926,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995198,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031335,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581075527,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094790,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119420,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162385,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248042,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275251,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305964,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310160,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423700,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439932,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499242,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535499,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602700,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581633051,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642414,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663559,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581722946,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048558,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084212,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165123,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300172,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582308196,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613823,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582644213,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582883232,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583064904,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098014,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583355983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584112036,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584751719,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585391566,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585785683,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585812700,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586473347,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593621,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586829543,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586878881,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587693112,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588196933,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588460294,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588504245,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792265,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588850830,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589204606,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589340723,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589683869,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1003",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864110,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496710,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580976382,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049194,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086887,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131511,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151766,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157855,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176460,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220305,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306618,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334051,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364540,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368704,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485092,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504156,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581563754,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600395,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663396,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704091,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713877,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735991,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581796402,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126414,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582161650,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243363,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399196,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582407204,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714751,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582746213,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582989775,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174312,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583203799,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583461983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584234884,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584886503,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585532078,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585929219,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585955340,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586621139,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586741061,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975623,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587024913,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587897400,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402085,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588665913,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588713094,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589015913,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589074155,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589430858,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589564939,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589910397,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867582,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580581542,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581143154,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231862,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256279,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581272883,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311301,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337612,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343803,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376365,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398369,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581500591,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531867,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:copy_one_pte"
      ],
      "caller_func": [
        "mm/memory.c:copy_one_pte"
      ]
    },
    {
      "addr": 18446744071581559540,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566336,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690319,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711483,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768804,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581815842,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874445,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920116,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931930,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953447,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582020202,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582362669,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398678,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478195,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688986,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582699175,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024961,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071982,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300046,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498086,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583804575,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641890,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:copy_page_to_iter_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585583414,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252190,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664168,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586694572,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587406286,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/dma-buf/heaps/heap-helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/heap-helpers.c:dma_heap_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587416051,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587546278,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811245,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587851712,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_release_rx_bufs",
        "drivers/net/xen-netfront.c:xennet_release_tx_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588752839,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589264111,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589513691,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589578449,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974360,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590039168,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590417275,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590570294,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590935919,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591078681,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1130",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514016,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578863326,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570822,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183106,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274457,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298327,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581310208,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352627,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378086,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581385538,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:__invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419968,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444305,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540760,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575515,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604196,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611824,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740063,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759275,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816996,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863583,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920637,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966804,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982494,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581999739,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582068650,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419565,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449378,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534525,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764100,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770570,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100482,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583148350,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414942,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606706,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583925215,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584762681,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:copy_page_to_iter_pipe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716310,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369918,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586774072,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586797308,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587485763,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587612902,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869158,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587916720,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_release_rx_bufs",
        "drivers/net/xen-netfront.c:xennet_release_tx_bufs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588773103,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589263256,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589519243,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589588385,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590015000,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590073352,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590476694,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590630278,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591000143,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591165444,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863326,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580573846,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201490,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291097,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315879,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581327168,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376147,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581398876,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441232,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465099,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597243,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_wp_page"
      ]
    },
    {
      "addr": 18446744071581626660,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634416,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768347,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786276,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844956,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894047,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945613,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994896,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009547,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029615,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582093811,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449450,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476166,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582561898,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582793049,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799293,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125954,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174127,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437790,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629953,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583952191,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584801290,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596742,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586254574,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654120,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586677676,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587367379,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587493846,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587748419,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587799853,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588657147,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589166931,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589416023,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589646622,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589929368,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589987834,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590401893,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590553610,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590930510,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591056083,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591099474,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1202",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582448,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864910,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743718,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441986,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535387,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561131,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581574752,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:end_page_writeback",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625123,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649068,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:lru_cache_add",
        "mm/swap.c:mark_page_accessed",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695120,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719868,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872421,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071581894177,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902304,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051003,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070052,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136204,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188751,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250253,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297088,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331167,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582406834,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771853,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:grow_dev_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582789024,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:dio_zero_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878749,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117305,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_page_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126366,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583467322,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517359,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787214,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:release_buffer_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989014,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584316271,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585226069,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586072598,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765294,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586778833,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587200984,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587225164,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935736,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588071524,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588344130,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_build_skb",
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400450,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589335028,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589887395,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590151680,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590402106,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590696359,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590757402,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591199413,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591364875,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591767054,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591898716,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591941880,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1206",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847584,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578860981,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360997,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957366,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884311,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581928304,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018545,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089363,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270565,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": [
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582303315,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_page",
        "mm/mlock.c:mlock_new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306495,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476959,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509562,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585613,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594710231,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582650429,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582732064,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738301,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784912,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798234,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836189,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582915994,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343271,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583450841,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583615543,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583990569,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049909,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584571971,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584935951,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586064753,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:pipe_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587295542,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045218,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588058401,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588505068,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535915,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589289282,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589436491,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589734750,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589800887,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591416270,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591709514,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591997092,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592324486,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592386279,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592860496,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593037790,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593486401,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593622684,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593667503,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1172",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582247616,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578863749,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431885,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252550,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229052,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348055,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582443911,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762449,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582797795,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_page",
        "mm/mlock.c:mlock_new_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801244,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992691,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028134,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097640,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455033,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175870,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269162,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317872,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583339777,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:set_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382472,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583470461,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583926671,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584218951,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616617,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584682181,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248078,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585647484,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587048570,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages",
        "lib/iov_iter.c:pipe_get_pages",
        "lib/iov_iter.c:copy_page_to_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588535878,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423826,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589438407,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589946412,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589982923,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590851334,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_create",
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591013691,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591356782,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591449399,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593181506,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593521418,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593811972,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594161580,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594236795,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_build_frag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594735616,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594929676,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595404800,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595552316,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595604185,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1224",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736848,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void get_page(struct page * page)
```

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578861637,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443917,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347382,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582429471,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550930,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582977909,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:numa_migrate_prep",
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583015340,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583237763,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307593,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596996363,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583392431,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489530,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536370,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561458,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:set_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583603137,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583687436,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584883091,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585477822,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585877583,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313280,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588815398,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589722978,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589738469,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590255676,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590292523,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591192221,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591367163,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591718558,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591765524,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/virtio_net.c:try_fill_recv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591864903,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593639849,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593987034,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594186464,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594549617,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594715621,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_clone_payload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595125144,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595321448,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595802755,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596060108,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596112991,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1410",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950416,
      "name": "get_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578872145,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579473645,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454422,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596447,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721522,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583172207,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194988,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583545889,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pmd_share"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597925846,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632697,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688644,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704202,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583751110,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:set_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583796701,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880254,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:lock_zspage",
        "mm/zsmalloc.c:lock_zspage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585115347,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712846,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586126255,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587598887,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:__iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iter_xarray_populate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589108278,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590060914,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590076468,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590596652,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590633739,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591539133,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591717563,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592462270,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592511478,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/virtio_net.c:virtnet_rq_alloc",
        "drivers/net/virtio_net.c:virtnet_rq_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592604711,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594415785,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone",
        "net/core/skbuff.c:__skb_zcopy_downgrade_managed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594771121,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594983136,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595352223,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595516885,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/ipv4/tcp_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:tcp_clone_payload"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595941847,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596163414,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596653363,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_fill_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596926988,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/xdp/xsk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xsk.c:xsk_build_skb_zerocopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596985763,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1464",
      "file": "net/mptcp/protocol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490383168,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_vcpu_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490463124,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "virt/kvm/arm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_set_pte",
        "virt/kvm/arm/mmu.c:stage2_get_pud",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings",
        "virt/kvm/arm/mmu.c:__create_hyp_mappings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491776060,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492339640,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492406128,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492453312,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492503520,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492528628,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492536000,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492556548,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492605664,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492718676,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753272,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492770164,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492776848,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903656,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492933364,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998256,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493040340,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493117612,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493145880,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493159784,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186268,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493259836,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493667444,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493715152,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493813648,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493999508,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494008496,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494371900,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494414016,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494674896,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494889868,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494923908,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495229360,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496111252,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497283688,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498196468,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498752160,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499513584,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499654844,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499968584,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500147636,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501129148,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501919100,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502205184,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502275220,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502618948,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502690576,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503082556,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503234980,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503628392,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225722024,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3226217772,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3226290572,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226326880,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226376008,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226394920,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226419156,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226461140,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226576252,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:insert_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226588004,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 3226591688,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226720580,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226757496,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226803008,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226869524,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 3227197852,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 3227242044,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 3227318256,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227463576,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227473088,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 3227807704,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3227844864,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 3228115112,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 3228303872,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3228334532,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 3228610876,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3229437696,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3230460100,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230954740,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 3231379780,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 3231981156,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3232107000,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3232520020,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:__tun_build_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 3233642724,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3234403420,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "sound/core/pcm_native.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/core/pcm_native.c:snd_pcm_mmap_data_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3234679156,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 3234962864,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3235017244,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3235329264,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3235392368,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 3235765544,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 3235907956,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 3236277392,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302382896,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/powerpc/kernel/vdso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/vdso.c:vdso_init",
        "arch/powerpc/kernel/vdso.c:vdso_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282844504,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:follow_huge_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284818452,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285572308,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285670560,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285727908,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285792116,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285823428,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285831972,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285860732,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285924460,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286058604,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286093080,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286135636,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286141148,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286305960,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286343232,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286425032,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286478456,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286579372,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286637540,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286654708,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286682524,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286785580,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287257940,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:attach_nobh_buffers",
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287321208,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287426556,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287648456,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287660320,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288106004,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288149264,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288488268,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288752428,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288793264,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289189520,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290361140,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291264656,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291430328,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291915608,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291950244,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292801156,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292978144,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293296528,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055294627904,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295335316,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295702216,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295775304,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296218996,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296300080,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296790996,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296978324,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297453620,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272091474,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272451004,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272525002,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272564158,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272581268,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272601720,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272636384,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272729238,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272746528,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272749428,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272852042,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272900030,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272912754,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272953462,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__buffer_migrate_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273015760,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273295574,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273328810,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273395492,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273514576,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273521864,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273798996,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273825548,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274033818,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274204866,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274229314,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274456858,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275176118,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275815452,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275971138,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276256612,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276722036,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276834770,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277046300,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277843148,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278230792,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278450734,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278509734,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278771028,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278820942,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279137394,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279269338,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279582056,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864110,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580465510,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945182,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018042,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055735,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100359,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120614,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581126703,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581145308,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189153,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275466,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302899,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333388,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581337552,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453940,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472892,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581532490,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569131,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632132,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672827,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682613,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704727,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581765138,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095150,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582130386,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212099,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367932,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582375940,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683487,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714949,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958511,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583143048,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172535,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430719,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203620,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584837687,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585294110,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585690195,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585716316,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311619,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431541,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586732631,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586781985,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587528376,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588008869,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272649,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319830,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588622297,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588680539,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589035226,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589169307,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589514765,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578857678,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580412486,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891246,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964170,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002983,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047479,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067606,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073663,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581092252,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135905,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221946,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260578,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277100,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281264,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581396264,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421564,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474293,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510699,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573188,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612282,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621255,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639220,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581703762,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032622,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067826,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582149875,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582305628,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582313636,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620655,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652117,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582895663,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080200,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109687,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367791,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138836,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584767511,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246622,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585549891,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585575500,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586152947,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586307797,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586599847,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587296536,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587721957,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985465,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588032614,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588334281,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588392523,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588760266,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588894299,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589240829,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864046,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580456758,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936430,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009242,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046935,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091559,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581111814,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581117903,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136508,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180353,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266666,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581294099,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324588,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328752,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445140,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464204,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581523802,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560443,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623444,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664139,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673925,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696039,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581756450,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085630,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120866,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202579,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358412,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582366420,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582673343,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704805,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947119,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583127080,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156567,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414495,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584187380,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839111,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585482478,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585879443,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585905356,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586569107,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695621,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930183,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586979473,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587853544,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588340645,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604473,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588651654,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589058473,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589116715,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589472090,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589606171,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589956029,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
  "name": "get_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864366,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580512422,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/relay.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/relay.c:relay_buf_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997998,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_mmap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070493,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108615,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153719,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:write_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174294,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_page_tail",
        "mm/swap.c:mark_page_lazyfree",
        "mm/swap.c:deactivate_page",
        "mm/swap.c:__lru_cache_add",
        "mm/swap.c:activate_page",
        "mm/swap.c:rotate_reclaimable_page",
        "mm/swap.c:get_kernel_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581180367,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/truncate.c:invalidate_mapping_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581199021,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:isolate_lru_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581243564,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_file_read_iter",
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330522,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358241,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581388560,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392832,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:special_mapping_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509621,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528927,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581588742,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625419,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:stable_tree_search",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689775,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730507,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740034,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763927,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581823615,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_page_migrate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582156206,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:create_empty_buffers",
        "fs/buffer.c:__getblk_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582193858,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO",
        "fs/direct-io.c:do_direct_IO"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276417,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:aio_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438044,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582446116,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582757286,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:__ext4_journalled_writepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788275,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found",
        "fs/ext4/mballoc.c:ext4_mb_use_best_found"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035443,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/jbd2/commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/commit.c:jbd2_journal_commit_transaction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220680,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_copy_page",
        "fs/fuse/dev.c:fuse_try_move_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250231,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_readpages_fill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510655,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "security/selinux/selinuxfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/selinuxfs.c:sel_mmap_policy_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584291956,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "lib/iov_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages_alloc",
        "lib/iov_iter.c:iov_iter_get_pages",
        "lib/iov_iter.c:iov_iter_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584944183,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/video/fbdev/core/fb_defio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585591662,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/virtio/virtio_balloon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585988643,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/virtio_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:pipe_to_sg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586013340,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/char/agp/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/generic.c:agp_generic_alloc_page",
        "drivers/char/agp/generic.c:agp_generic_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586681395,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/dma-buf/udmabuf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/udmabuf.c:udmabuf_vm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586801653,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_vma_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587037815,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587086673,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587968456,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "drivers/md/md-bitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:read_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588476117,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:pskb_carve",
        "net/core/skbuff.c:skb_try_coalesce",
        "net/core/skbuff.c:skb_segment",
        "net/core/skbuff.c:skb_append_pagefrags",
        "net/core/skbuff.c:skb_shift",
        "net/core/skbuff.c:skb_split",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:skb_zerocopy",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__pskb_copy_fclone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742153,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/filter.c:bpf_msg_push_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588791462,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_msg_clone",
        "net/core/skmsg.c:sk_msg_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589097657,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589156539,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589518133,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv4/tcp_bpf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654459,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590006871,
      "name": "get_page",
      "external": false,
      "loc": "include/linux/mm.h:1016",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_snd"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void get_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void get_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void get_page(struct page * page)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void get_page(struct page * page)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void get_page(struct page * page)
```
</details>
</li>
</ul>
