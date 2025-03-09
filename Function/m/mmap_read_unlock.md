# Function: <code>mmap_read_unlock</code>

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
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579400810,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area_access_error",
        "arch/x86/mm/fault.c:bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557677,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642913,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579802319,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580272294,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
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
      "addr": 18446744071580325865,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580706409,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_output.c:trace_user_stack_print"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149154,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581233191,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283502,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299189,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405521,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507342,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554190,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557279,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580268,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602452,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603285,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650374,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/process_vm_access.c:process_vm_rw_single_vec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686345,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_remove",
        "mm/madvise.c:madvise_willneed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721702,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785800,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:lookup_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817116,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868990,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940710,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966161,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027975,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
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
      "addr": 18446744071582030625,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043580,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582113054,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468856,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512369,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582738506,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774575,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586879437,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587881338,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587899776,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590025803,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591068447,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:59",
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864665,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269301,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270621,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402627,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530192,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579623432,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793685,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249332,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311354,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580695368,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581189095,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275764,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327547,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343203,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581443644,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581547522,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598951,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601687,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625988,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649612,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650449,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698529,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581732645,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768748,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833295,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:lookup_node"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071581864892,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914719,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat_array",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987699,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582012427,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_count_precharge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582076721,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582078933,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/frame_vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/frame_vector.c:get_vaddr_frames"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092543,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582159323,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582525864,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570925,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582714302,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582725310,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582812094,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582847826,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586929590,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587943574,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587964575,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590080702,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591133298,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
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
      "addr": 18446744071579530192,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581824736,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582071600,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864646,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579269639,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272010,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277812,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405387,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579534432,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579629997,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579801570,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580254465,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314727,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580699733,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581056199,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207092,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300850,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handler_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339001,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362465,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464444,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570460,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621796,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581623965,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645214,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670490,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671674,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720235,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581761859,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581797123,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581864142,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071581895377,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940086,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992748,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015472,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035176,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582103150,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582117612,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183400,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582554664,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582587397,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743296,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582753963,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840818,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876239,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811669,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/iommu/intel/svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587825192,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846588,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/pci/vfio_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589995194,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591064127,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
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
      "addr": 18446744071579534432,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581855056,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071582096592,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578866224,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311617,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314122,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320575,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579467905,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579579117,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579606800,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/exit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:exit_mm",
        "kernel/exit.c:exit_mm"
      ]
    },
    {
      "addr": 18446744071579706413,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579897970,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580405800,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/futex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580468263,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877205,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581281223,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:task_vma_seq_stop",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407760,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/bpf/stackmap.c:do_up_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581447327,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545285,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587420,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610564,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719091,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581834975,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889198,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581891437,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581913237,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939753,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940969,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992539,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582044450,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582081502,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155678,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:lookup_node"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071582173411,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190081,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582244717,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582294985,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318166,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331906,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592226781,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419261,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582433990,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582500824,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582870792,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906640,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sqe_buffer_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070196,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583080874,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173582,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583209860,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502036,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587430160,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/iommu/io-pgfault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588430348,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452652,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590764874,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591907261,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
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
      "addr": 18446744071579606800,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582148384,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071582411408,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578862227,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369820,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372205,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379255,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579544765,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579669773,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579708570,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579805407,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010398,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580625910,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580662126,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108134,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581575054,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:do_mmap_read_unlock",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731723,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790887,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896226,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943955,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970702,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095270,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582233233,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582287183,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289381,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319640,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349150,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350102,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415355,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582485337,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520170,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582610965,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071582632275,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582651938,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582717160,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781273,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810226,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834482,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594005735,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582933596,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071582950825,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_walk_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017081,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583434345,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583548691,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559353,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664662,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583706575,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585138956,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585964326,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588745578,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/iommu/io-pgfault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/io-pgfault.c:iopf_handle_single"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828305,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589853645,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/vfio/pci/vfio_pci_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592397598,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593627572,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
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
      "addr": 18446744071582603376,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071582924336,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578864478,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435790,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579445738,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449986,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579455668,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579650486,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579789929,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579834274,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579939295,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580173174,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891814,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932068,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417039,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581952526,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:do_mmap_read_unlock",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582139419,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582216864,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318812,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378451,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582401626,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488494,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570328,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719137,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    },
    {
      "addr": 18446744071582780006,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782640,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__do_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818100,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_sys_brk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582850265,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:__do_sys_mremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851772,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582923195,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582999689,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038400,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120660,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134191,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071583172705,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583244783,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583313438,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353657,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379477,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427592,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583489295,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic"
      ]
    },
    {
      "addr": 18446744071583578326,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584023865,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584149955,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584161340,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:create_elf_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584271569,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317691,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585863772,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586849408,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590231817,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594248735,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595557769,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:141",
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
      "addr": 18446744071582704288,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583124016,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583479920,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578862396,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579447855,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457824,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462155,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579467839,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664899,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579837472,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579883252,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579989183,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580240672,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975689,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018475,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581513580,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581752975,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
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
      "addr": 18446744071582140638,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:do_mmap_read_unlock",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336635,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417290,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582519994,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586731,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:do_sync_mmap_readahead",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607660,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582704036,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777619,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932897,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582996460,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582999015,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032389,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067777,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583139593,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583207967,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246936,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330926,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583344513,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071583388978,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583466222,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532781,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572970,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583599720,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648347,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704921,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071583797646,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584248713,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584502033,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584547688,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586095709,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115883,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590551859,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594636054,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596066100,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:172",
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
      "addr": 18446744071583336192,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071583696560,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void mmap_read_unlock(struct mm_struct * mm)
```

```json
{
  "name": "mmap_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578872907,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vdso/vma.c:vdso_join_timens"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477663,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579487840,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579492219,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579497951,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579673727,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/kernel/shstk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/shstk.c:shstk_pop_sigframe",
        "arch/x86/kernel/shstk.c:shstk_pop_sigframe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579698869,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579877360,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:replace_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579919716,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:exit_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028591,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326361,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069529,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/futex/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/futex/core.c:fault_in_user_writeable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581114372,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:acct_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625126,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/trace/trace_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581869795,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
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
      "addr": 18446744071582287694,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/bpf/task_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/task_iter.c:do_mmap_read_unlock",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582502891,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582585001,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_addr_filters_apply"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688874,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:find_active_uprobe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582777916,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582873556,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582939142,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_falloc_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583107969,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583167692,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:fault_dirty_shared_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583178391,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213626,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583249713,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/msync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322713,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/process_vm_access.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583443535,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481463,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583565262,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583574867,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:do_get_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    },
    {
      "addr": 18446744071583626322,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583657806,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727122,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pages_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766406,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583793896,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843179,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:kill_accessing_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583901720,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071584004478,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:exec_mmap",
        "fs/exec.c:get_arg_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584454050,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_move",
        "fs/userfaultfd.c:userfaultfd_remove",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726059,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584779519,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344813,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_dump_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587394573,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_pin_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590908675,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "drivers/iommu/iommu-sva.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595439343,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596933938,
      "name": "mmap_read_unlock",
      "external": false,
      "loc": "include/linux/mmap_lock.h:170",
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
      "addr": 18446744071583571808,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071583890768,
      "name": "mmap_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void mmap_read_unlock(struct mm_struct * mm)
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
