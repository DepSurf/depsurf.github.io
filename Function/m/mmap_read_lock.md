# Function: <code>mmap_read_lock</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401214,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557804,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642488,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272254,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:futex_lock_pi",
        "kernel/futex.c:fixup_pi_state_owner",
        "kernel/futex.c:futex_requeue",
        "kernel/futex.c:futex_wake_op"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325800,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706349,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_output.c:trace_user_stack_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149072,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233132,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512946,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557233,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603364,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650067,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/process_vm_access.c:process_vm_rw_single_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686308,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_remove",
        "mm/madvise.c:madvise_willneed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721631,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786268,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816852,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868883,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935060,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972454,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582027833,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030144,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043523,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112880,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512277,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586879329,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881172,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899817,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590025651,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591068395,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:44",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864569,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269038,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270546,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403052,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530240,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579623015,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249283,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311263,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580695270,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581189000,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275692,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581553177,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601624,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650552,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698201,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581732580,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768629,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581832848,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864596,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914565,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat_array",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581977229,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581996165,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_count_precharge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076535,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582078795,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092479,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582159120,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570827,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929463,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587943430,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964621,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080245,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133234,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530240,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582071648,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864553,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269274,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271938,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405895,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534480,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579629308,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254419,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314639,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699638,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581207000,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300653,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handler_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576163,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624080,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671775,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719907,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581761608,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581797035,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863696,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581895067,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939970,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992430,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582005307,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582049258,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582102967,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582117551,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183200,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587312,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811481,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825032,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846634,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589994741,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591064066,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534480,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582096640,
      "name": "mmap_read_lock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866137,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311226,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314050,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579468470,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579029,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606832,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579705724,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405763,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468175,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877110,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581447241,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545381,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840787,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891544,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941082,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992211,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582043680,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582081414,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155232,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582173379,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189771,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582244590,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294670,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307743,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355991,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592226626,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419079,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582433935,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582500624,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906543,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584501979,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430039,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/iommu/io-pgfault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588430205,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452695,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590764238,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591907199,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606832,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582411456,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578862137,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369454,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372132,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579545362,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669685,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708457,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579804919,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580625873,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662038,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108036,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581790802,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896344,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582233166,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289488,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350220,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414990,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582485268,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520089,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610434,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582632243,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651627,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716994,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780982,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803714,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853869,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594005575,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933402,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582950767,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017470,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138899,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964237,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745455,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/iommu/io-pgfault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828019,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589853688,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592396993,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593627511,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924400,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864404,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435727,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579445499,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449951,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579651093,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789846,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579834161,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579938807,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891777,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932013,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416944,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582216795,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318651,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719000,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782584,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817991,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851885,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582922830,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582999620,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038323,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120603,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133666,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583172153,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244562,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313158,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583354015,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583400646,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427493,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489114,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071583584632,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863715,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586849316,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590231695,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594248145,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595557707,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:114",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583480000,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578862321,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447785,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457579,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462117,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579837367,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883137,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579988417,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975649,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018413,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513476,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581752926,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/trace/trace_events_user.c:update_enable_bit_for",
        "kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup",
        "kernel/trace/trace_events_user.c:user_event_mm_fault_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417218,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519819,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582920272,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998956,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032267,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067890,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139233,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583207890,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246855,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330895,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343986,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583388415,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465965,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532486,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583573444,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583621126,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648245,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704720,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
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
      "addr": 18446744071583801609,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095651,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115806,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590551733,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594635956,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596066038,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:145",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696624,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void mmap_read_lock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_lock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578872832,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477593,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487595,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492181,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579877254,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919601,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580027825,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069489,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114310,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625014,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581869746,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/trace/trace_events_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:update_enable_bit_for",
        "kernel/trace/trace_events_user.c:user_event_enabler_create",
        "kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup",
        "kernel/trace/trace_events_user.c:user_event_mm_fault_in"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584929,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688699,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583094416,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178332,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213489,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249826,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322353,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583443458,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481382,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565189,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583574801,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583625728,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657549,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583726838,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766585,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816070,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843077,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583901519,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
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
      "addr": 18446744071584007817,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584453983,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_move"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344755,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394516,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590908549,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595439249,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596933876,
      "name": "mmap_read_lock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:143",
      "file": "net/xdp/xdp_umem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890832,
      "name": "mmap_read_lock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void mmap_read_lock(struct mm_struct * mm)
```
</details>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
