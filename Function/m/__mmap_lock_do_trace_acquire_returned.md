# Function: <code>__mmap_lock_do_trace_acquire_returned</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581556944,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:219",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:mmap_read_lock",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:xol_add_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:oom_reap_task_mm",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_page",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/madvise.c:madvise_remove",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat_array",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_count_precharge",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/io_uring.c:io_unaccount_mem",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556944,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581579760,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:230",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:mmap_read_lock",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sys.c:prctl_set_mm_exe_file",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:oom_reaper",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_page",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_zap_and_vma_lock",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579760,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844752,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:234",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:mmap_read_lock",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:pin_user_pages_locked",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_locked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free",
        "mm/sparse-vmemmap.c:vmemmap_remap_free",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:unstable_tree_search_insert",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:__bprm_mm_init",
        "fs/exec.c:get_arg_page",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/io_uring.c:io_sqe_buffer_register",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/coredump.c:coredump_wait",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "drivers/iommu/io-pgfault.c:iopf_handle_single",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844752,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582237536,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:234",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_vma",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex/core.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:handler_chain",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:__create_xol_area",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:internal_get_user_pages_fast",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__get_user_pages_remote",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/sparse-vmemmap.c:vmemmap_remap_alloc",
        "mm/sparse-vmemmap.c:vmemmap_remap_free",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:get_arg_page",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "io_uring/io_uring.c:io_pin_pages",
        "drivers/iommu/io-pgfault.c:iopf_handle_single",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_zap_and_vma_lock",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_pin_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582237536,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582727856,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:234",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_vma",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex/core.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:xol_add_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:get_arg_page",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "io_uring/rsrc.c:io_pin_pages",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582727856,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582943232,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:234",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/process_64.c:prctl_enable_tagged_addr",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_vma",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex/core.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:user_events_ioctl_reg",
        "kernel/trace/trace_events_user.c:update_enable_bit_for",
        "kernel/trace/trace_events_user.c:user_event_mm_remove",
        "kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup",
        "kernel/trace/trace_events_user.c:user_event_mm_fault_in",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:xol_add_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_alloc",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_free",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:get_arg_page",
        "fs/exec.c:get_arg_page",
        "fs/exec.c:get_arg_page",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "io_uring/rsrc.c:io_pin_pages",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582943232,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
```

```json
{
  "name": "__mmap_lock_do_trace_acquire_returned",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583118480,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "external": true,
      "loc": "mm/mmap_lock.c:234",
      "file": "mm/mmap_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:map_vdso",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "arch/x86/kernel/process_64.c:prctl_enable_tagged_addr",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/shstk.c:shstk_pop_sigframe",
        "arch/x86/kernel/shstk.c:alloc_shstk",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/exit.c:exit_mm",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/sys.c:prctl_set_vma",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sys.c:prctl_set_mm_map",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/futex/core.c:fault_in_user_writeable",
        "kernel/acct.c:acct_collect",
        "kernel/trace/trace_events_user.c:user_events_ioctl_unreg",
        "kernel/trace/trace_events_user.c:update_enable_bit_for",
        "kernel/trace/trace_events_user.c:user_event_enabler_create",
        "kernel/trace/trace_events_user.c:user_event_mm_remove",
        "kernel/trace/trace_events_user.c:user_event_enabler_fault_fixup",
        "kernel/trace/trace_events_user.c:user_event_mm_fault_in",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_new",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:xol_add_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/oom_kill.c:__do_sys_process_mrelease",
        "mm/oom_kill.c:oom_reaper",
        "mm/vmscan.c:walk_mm",
        "mm/util.c:vm_mmap_pgoff",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages_unlocked",
        "mm/gup.c:get_user_pages",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:get_user_pages_remote",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:__gup_longterm_locked",
        "mm/gup.c:get_dump_page",
        "mm/gup.c:fault_in_safe_writeable",
        "mm/gup.c:__mm_populate",
        "mm/gup.c:fixup_user_fault",
        "mm/gup.c:fixup_user_fault",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_pages",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:__do_sys_munlockall",
        "mm/mlock.c:__do_sys_mlockall",
        "mm/mlock.c:__ia32_sys_munlock",
        "mm/mlock.c:__x64_sys_munlock",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:vm_brk_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__vm_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:expand_stack",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:__ia32_sys_pkey_free",
        "mm/mprotect.c:__x64_sys_pkey_free",
        "mm/mprotect.c:__do_sys_pkey_alloc",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:do_madvise",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/mmu_notifier.c:mmu_notifier_register",
        "mm/ksm.c:__ksm_exit",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:cmp_and_merge_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__khugepaged_exit",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/ptdump.c:ptdump_walk_pgd",
        "fs/exec.c:alloc_bprm",
        "fs/exec.c:exec_mmap",
        "fs/exec.c:setup_arg_pages",
        "fs/exec.c:get_arg_page",
        "fs/exec.c:get_arg_page",
        "fs/exec.c:get_arg_page",
        "fs/userfaultfd.c:userfaultfd_move",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/aio.c:aio_setup_ring",
        "fs/binfmt_elf.c:create_elf_tables",
        "fs/compat_binfmt_elf.c:create_elf_tables",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "security/tomoyo/domain.c:tomoyo_dump_page",
        "io_uring/rsrc.c:io_pin_pages",
        "drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/xdp/xdp_umem.c:xdp_umem_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583118480,
      "name": "__mmap_lock_do_trace_acquire_returned",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __mmap_lock_do_trace_acquire_returned(struct mm_struct * mm, bool write, bool success)
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
