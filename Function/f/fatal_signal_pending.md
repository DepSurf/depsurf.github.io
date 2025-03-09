# Function: <code>fatal_signal_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858904,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:tracehook_report_syscall_exit",
        "arch/x86/entry/common.c:syscall_trace_enter_phase2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284059,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425202,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139384,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_phase2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580452142,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580472486,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580487787,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580514454,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522578,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580552763,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636827,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:try_to_compact_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580658550,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808242,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924425,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973918,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581019569,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581072310,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226927,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314622,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817171,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009955,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274450,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630817,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648250,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "crypto/ablkcipher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/ablkcipher.c:crypto_alloc_ablkcipher"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583230103,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_pci22_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585792911,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:2910",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_live_table_for_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858619,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284947,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579437618,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580171579,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580527565,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549253,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600287,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580606906,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580648459,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754414,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580767204,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932717,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072018,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128958,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147295,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178847,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581234209,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394244,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481483,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721429,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581805100,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012935,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223272,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493746,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880454,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538807,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586191113,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3187",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858574,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579300369,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457970,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580212235,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590910,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580612901,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667317,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674169,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580715595,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819702,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832756,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147373,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204025,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581221908,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255969,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581312007,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472618,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562159,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575988,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665634,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581894510,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102990,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582312776,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584962,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582976982,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583675139,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586395241,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched.h:3343",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858232,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298158,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579445682,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580221798,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580621062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580641290,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700617,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706656,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580750295,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580860099,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875644,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975777,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581048619,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192712,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252914,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268891,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305325,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581363640,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527934,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590669,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612607,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636435,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722089,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581881168,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933722,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582067126,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089011,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582397525,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582676950,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026800,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583716531,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586498424,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:322",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578858053,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318808,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474098,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274470,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580701926,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580724037,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786056,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580792178,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837543,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951088,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580970785,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159399,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322758,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384602,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407980,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444985,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581505105,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670270,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735283,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755451,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781312,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867913,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582031225,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082586,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216577,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238620,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582548274,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582830502,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583192018,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974129,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "drivers/pci/access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/access.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586965831,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:323",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_grab_bdev_for_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578859836,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_trace_enter",
        "arch/x86/entry/common.c:tracehook_report_syscall_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329396,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416829,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579490434,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333618,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393892,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834346,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580859384,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919322,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580930031,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580974183,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087216,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105314,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302587,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472828,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535192,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563241,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603541,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581661758,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833913,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902645,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924614,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953875,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050870,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582219527,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270630,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406656,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428443,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740268,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018501,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402992,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241298,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587262150,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:351",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578860062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354689,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579456390,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579523906,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580388538,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447092,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580902464,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927912,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580994910,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006604,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050855,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165136,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581185154,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386231,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567002,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621242,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648757,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688869,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581748222,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921190,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992972,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009942,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040067,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143334,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/iomap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582314375,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582369270,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582505920,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527963,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798264,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844028,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134700,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522320,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839073,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331026,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587442422,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:360",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368353,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472698,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543570,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580441579,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580501392,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000146,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024381,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069354,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114427,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236085,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581256089,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581413758,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497765,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678742,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733564,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765333,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806981,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581865486,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058443,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128867,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582148916,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201265,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302254,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582482372,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582537546,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663573,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582696973,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582972499,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019246,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322053,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710783,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029250,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584526107,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720797,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:365",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372593,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579498804,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579569682,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258639,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580490597,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549200,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054994,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079725,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125322,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171387,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581294549,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314761,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474798,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486549,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562293,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750675,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807116,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837541,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879573,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581937886,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136235,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582203974,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582226116,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282097,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316395,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401278,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582581604,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638490,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765573,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799165,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079107,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125438,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427381,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583820399,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133118,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167817,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584661227,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585902256,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924525,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578866383,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:__syscall_return_slowpath",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401184,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527661,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602498,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580327823,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580576364,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636800,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237294,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263005,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312344,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363984,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484733,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_finished",
        "mm/compaction.c:compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507172,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654868,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691827,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772714,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971025,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027507,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060084,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112100,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582169107,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361459,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582442511,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464293,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539826,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582566752,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605050,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582694713,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582890275,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949435,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077243,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111490,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583397520,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583445630,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783969,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215596,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584523315,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584566070,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585345019,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586640315,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587408116,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588772797,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:366",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579403022,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579510017,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579582706,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580137664,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313295,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565737,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580626782,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305485,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read_get_pages",
        "mm/filemap.c:generic_file_buffered_read_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353692,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407584,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526496,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547353,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702542,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736691,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820874,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582019661,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075988,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153403,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582215635,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409477,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414662,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496340,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582521352,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610587,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582638320,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678042,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765577,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582962568,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583024155,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152258,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190514,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583513168,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558350,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906049,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334003,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584632469,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584684138,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585496907,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586749339,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476192,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588792397,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:379",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579405861,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579513330,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579586386,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142485,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580316783,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580568071,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628974,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296074,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323149,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370603,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428816,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548656,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570294,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737339,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765042,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849981,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045921,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102343,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177451,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582240563,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436620,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582441862,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582522836,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550661,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582667190,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706812,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713227,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582773358,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582794585,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988782,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050913,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177366,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583218422,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536284,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583581778,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933313,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584368547,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668433,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584712395,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585376107,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586632715,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587357930,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587824366,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588677341,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:380",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468436,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579584920,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660306,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:task_join_group_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580286133,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580471263,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580738047,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800446,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541020,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568668,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612050,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:pagefault_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619069,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681024,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab_node",
        "mm/vmscan.c:drop_slab_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812205,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834816,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582014201,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047699,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141245,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353302,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417463,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582494923,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759372,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582765653,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582838820,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866858,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979820,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io-wq.c:create_io_worker",
        "fs/io-wq.c:create_worker_cont"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992763,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583033372,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039867,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583100574,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583119752,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583324849,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388529,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515629,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562134,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583894235,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583939794,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584297601,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763715,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585084800,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585136309,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585837742,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587179931,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924341,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588429537,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589364605,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:378",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int fatal_signal_pending(struct task_struct * p)
```

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579545326,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579670428,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579782426,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459453,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580664367,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951722,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025084,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891443,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581923168,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972302,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:pagefault_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982400,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057821,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582201250,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227306,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385928,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vm_area_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457148,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478690,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593747,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852914,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931911,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583020591,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583308845,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315073,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399380,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425267,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465429,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507257,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583514526,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583581646,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583609217,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832823,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902702,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584047826,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584098793,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584470629,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520524,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584896516,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585446797,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811207,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585867098,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586031574,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587029813,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275336,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828721,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590840088,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:408",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664224,
      "name": "fatal_signal_pending",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int fatal_signal_pending(struct task_struct * p)
```

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579651044,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790737,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579915130,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_trap_notify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706557,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935263,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245583,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326924,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582324832,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360768,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582406750,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:pagefault_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419076,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582530509,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:lru_gen_shrink_lruvec",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687911,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725576,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918787,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582971164,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992226,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111780,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399605,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487686,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585999,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583895309,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902257,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583985956,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584014209,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584056091,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584103985,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584113136,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584185006,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215481,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584456110,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584528286,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584679583,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584732393,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585134261,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585191301,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585604084,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586205069,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592919,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586650783,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586867398,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588208101,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590839707,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592531802,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784672,
      "name": "fatal_signal_pending",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int fatal_signal_pending(struct task_struct * p)
```

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664756,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579838385,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071579964937,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:unhandled_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783389,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581021993,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340543,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421756,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526169,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582563796,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612734,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:pagefault_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582624292,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733949,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897474,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582919598,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134784,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182997,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202602,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321844,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583620087,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703463,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071583803183,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584119359,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125758,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584209268,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584236644,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283363,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331959,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584339234,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584412574,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445156,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584685020,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584757326,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584905298,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_try_to_trim_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584955701,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363605,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585420351,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585834809,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586443181,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851126,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586909546,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587133500,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588483781,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591181967,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592961701,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:409",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831440,
      "name": "fatal_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583696720,
      "name": "fatal_signal_pending",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int fatal_signal_pending(struct task_struct * p)
```

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579698765,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579874419,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": [
        "kernel/fork.c:copy_process"
      ]
    },
    {
      "addr": 18446744071580004265,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:ptrace_signal",
        "kernel/signal.c:ptrace_trap_notify",
        "kernel/signal.c:unhandled_signal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871773,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/entry/common.c:syscall_exit_work",
        "kernel/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120089,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447551,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530595,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695081,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734660,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:filemap_get_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784302,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:pagefault_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796127,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582901869,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:drop_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069346,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:__compact_finished",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093742,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317840,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367109,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:__alloc_contig_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438139,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583815015,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904811,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071584009391,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584334272,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/remap_range.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/remap_range.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584342622,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_expand_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584423764,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_send_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451730,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584500163,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584549780,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584557442,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/verity/read_metadata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584633310,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:dump_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667668,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/buffered-io.c:iomap_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726415,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:do_pagemap_scan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584917836,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584990350,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585109566,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_interrupted"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585186725,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585598341,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585655137,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084748,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586709037,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm_node",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128443,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587187578,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587419723,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "io_uring/io-wq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io-wq.c:create_io_worker",
        "io_uring/io-wq.c:create_worker_cont"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781541,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591528111,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "drivers/dma-buf/heaps/system_heap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/heaps/system_heap.c:system_heap_allocate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593711829,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:401",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579869312,
      "name": "fatal_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071583890928,
      "name": "fatal_signal_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490217412,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm64/kernel/ptrace.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490292904,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm64/kernel/sys_compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/sys_compat.c:compat_arm_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503955752,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm64/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490631048,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490731632,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491501440,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491767148,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491825284,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492412920,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492442360,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492496556,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492551212,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492701048,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492721636,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492885828,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492904780,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492995584,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493204508,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272320,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493301572,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357000,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493424180,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493681404,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493770704,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493791260,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493855852,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493896048,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494003704,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494230640,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494290792,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494432016,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494469280,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494784360,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494835200,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495218972,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495626976,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982980,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496020656,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496910220,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498721616,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501152664,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224424836,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:syscall_trace_exit",
        "arch/arm/kernel/ptrace.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3224435556,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:arm_syscall"
      ],
      "caller_func": []
    },
    {
      "addr": 3236559256,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/arm/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3224709560,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224783796,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 3225483004,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3225715536,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 3225776796,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226296696,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226318952,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3226370020,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226431572,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226539156,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:compact_unlock_should_abort",
        "mm/compaction.c:compact_unlock_should_abort"
      ],
      "caller_func": []
    },
    {
      "addr": 3226552224,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 3226684704,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226696272,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226835040,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878452,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3226905528,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226946104,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings",
        "fs/exec.c:copy_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 3227005244,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 3227213668,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 3227281076,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3227301180,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 3227375564,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3227467940,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227659968,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 3227723312,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 3227866440,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 3227905728,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3228204792,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 3228254492,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 3228594920,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3228984988,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 3229323672,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 3229364244,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 3230185920,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 3231348368,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3233672196,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282267592,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave",
        "arch/powerpc/kernel/ptrace.c:do_syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282715152,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/powerpc/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283450676,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283554220,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284461088,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284811320,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284897748,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285678848,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285716872,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285784376,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285853688,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286035180,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286066260,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286282844,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286307696,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286420396,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286710592,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286799520,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286841148,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286899792,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286982060,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287283880,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287374784,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287409132,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287483732,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287532744,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287654096,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287928344,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288004712,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288180436,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288226576,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288618520,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288681812,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289127500,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289751192,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290208076,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290254284,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291004532,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291874564,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294670992,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271344826,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/riscv/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_exit",
        "arch/riscv/kernel/ptrace.c:do_syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271359060,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271386456,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271441752,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272086544,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272137070,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272518924,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272558364,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272597398,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272702368,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714766,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272826060,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272829428,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272898740,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272982358,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024558,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273045554,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273079374,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings",
        "fs/exec.c:copy_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273127128,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273304992,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273363894,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:do_epoll_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273384180,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273425090,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273454490,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273518322,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273684002,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273733942,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273844812,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273874630,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274116332,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274158300,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274437986,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274784414,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275082736,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275112520,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275597540,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276234684,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277868366,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862273,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368497,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472468,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545986,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580227439,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459397,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518000,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581023842,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048573,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581094170,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581140235,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263397,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283609,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443646,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581455397,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531029,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719411,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775852,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806277,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848309,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581906622,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582104971,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172710,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582194852,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582250833,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285131,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582370014,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582550340,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607226,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582734309,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582767901,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583047843,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094174,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583396117,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583789135,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101854,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136553,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611691,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585663248,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586459521,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_wait_ready",
        "drivers/nvme/host/core.c:nvme_wait_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587555501,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578855313,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298964,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401380,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579474722,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580174927,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406453,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466048,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969938,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995853,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041338,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581087179,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210053,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229618,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386030,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581397648,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472853,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658283,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714016,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743941,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785973,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581844206,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042411,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105361,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582132334,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188561,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582222891,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307710,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582487508,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582544394,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671477,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582705069,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582984995,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031326,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333205,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726191,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037534,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584072115,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584541515,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585523168,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586335761,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_shutdown_ctrl",
        "drivers/nvme/host/core.c:nvme_wait_ready",
        "drivers/nvme/host/core.c:nvme_wait_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587323597,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862209,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368417,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579472388,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579543266,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580218911,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580450645,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580509248,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581015042,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581039773,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085370,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131435,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581254597,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274809,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434846,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446597,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522341,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581710723,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767164,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797589,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839621,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581897934,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095451,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582163190,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582185332,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582241313,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275611,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360494,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582540452,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582597338,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582724165,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758141,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583036451,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583082782,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379893,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583772895,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085614,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120313,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584611387,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852656,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587880669,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588907459,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "net/netfilter/nfnetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nfnetlink.c:nfnetlink_rcv_batch"
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
  "name": "fatal_signal_pending",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578862526,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:syscall_slow_exit_work",
        "arch/x86/entry/common.c:syscall_trace_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579376862,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:mm_fault_error"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579504189,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579576258,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:task_set_jobctl_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580271679,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:kimage_alloc_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580506281,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/seccomp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:__seccomp_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580565584,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:__rb_allocate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076304,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:uprobe_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101401,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_perform_write",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147293,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193899,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318437,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:try_to_compact_pages",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581338684,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499342,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:alloc_contig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581511061,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587294,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778193,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_out_of_memory"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835853,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866757,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:vfs_dedupe_file_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909165,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581967549,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:__generic_block_fiemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168301,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:cont_write_begin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231502,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582257364,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582320945,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_actor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354171,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440190,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/iomap/buffered-io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582621588,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/dir.c:ext4_readdir"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679402,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/fsmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fsmap.c:ext4_getfsmap_helper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808981,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_all_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843057,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ext4/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/namei.c:ext4_htree_fill_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125587,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/fat/fatent.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fat/fatent.c:fat_trim_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172062,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "fs/ecryptfs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/read_write.c:ecryptfs_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583476916,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873887,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "crypto/api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_tfm",
        "crypto/api.c:crypto_alloc_base",
        "crypto/api.c:crypto_alloc_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188441,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584215253,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:ioc_rqos_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584719083,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/pci/vpd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/vpd.c:pci_vpd_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585959445,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/char/mem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/mem.c:write_mem",
        "drivers/char/mem.c:read_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587997645,
      "name": "fatal_signal_pending",
      "external": false,
      "loc": "include/linux/sched/signal.h:357",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_prepare_ioctl"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int fatal_signal_pending(struct task_struct * p)
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
