# Function: <code>find_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697152,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2041",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:__access_remote_vm",
        "mm/memory.c:print_vma_addr",
        "mm/mincore.c:SyS_mincore",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:SyS_brk",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mprotect.c:SyS_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:SyS_msync",
        "mm/msync.c:SyS_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:SyS_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_mbind",
        "mm/ksm.c:find_mergeable_vma",
        "mm/ksm.c:ksm_scan_thread",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:SyS_move_pages",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/proc/base.c:proc_map_files_lookup",
        "ipc/shm.c:do_shmat",
        "ipc/shm.c:SyS_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697152,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811536,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:1940",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:SyS_mincore",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:SyS_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:SyS_msync",
        "mm/msync.c:SyS_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:SyS_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811536,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876896,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2093",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:SyS_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:SyS_msync",
        "mm/msync.c:SyS_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:SyS_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876896,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921824,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2115",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:SyS_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:SyS_msync",
        "mm/msync.c:SyS_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921824,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021440,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2131",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:SyS_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:SyS_remap_file_pages",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:SyS_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:SyS_msync",
        "mm/msync.c:SyS_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:SyS_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:SYSC_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:SyS_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021440,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581156800,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2191",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581156800,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236592,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2226",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__ia32_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/madvise.c:__x64_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/migrate.c:do_pages_stat",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236592,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581310864,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2227",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_snapshot",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581310864,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581369408,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581369408,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581575157,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2234",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_vma_prev"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:do_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567232,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581620693,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2300",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_vma_prev"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:do_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat_array",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612672,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581643109,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2304",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_vma_prev"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635232,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911093,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2273",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_vma_prev"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903104,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582308080,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2301",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:generic_get_unmapped_area_topdown",
        "mm/mmap.c:generic_get_unmapped_area",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:__do_sys_mremap",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_populate",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:do_get_mempolicy",
        "mm/mempolicy.c:mbind_range",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:add_page_for_migration",
        "mm/huge_memory.c:split_huge_pages_pid",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns",
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308080,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582828306,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:1830",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:vma_merge",
        "mm/mmap.c:__vma_adjust",
        "mm/mmap.c:__vma_adjust"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/memory.c:print_vma_addr",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:move_vma",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mwriteprotect_range",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804352,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583038822,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:1858",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma_locked"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:gup_vma_lookup",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583017984,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583220086,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:1890",
      "file": "mm/mmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mmap.c:find_extend_vma_locked"
      ],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/kernel/cpu/sgx/ioctl.c:__sgx_encl_add_page",
        "arch/x86/kernel/shstk.c:shstk_pop_sigframe",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/bpf/task_iter.c:bpf_find_vma",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:gup_vma_lookup",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/memory.c:lock_mm_and_find_vma",
        "mm/msync.c:__do_sys_msync",
        "mm/msync.c:__do_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/madvise.c:madvise_walk_vmas",
        "mm/mempolicy.c:migrate_to_node",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/mempolicy.c:queue_pages_test_walk",
        "mm/huge_memory.c:vma_adjust_trans_huge",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583197632,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492774944,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:arm64_notify_segfault",
        "arch/arm64/mm/fault.c:do_page_fault",
        "virt/kvm/kvm_main.c:__gfn_to_pfn_memslot",
        "virt/kvm/kvm_main.c:kvm_host_page_size",
        "virt/kvm/arm/mmu.c:kvm_arch_prepare_memory_region",
        "virt/kvm/arm/mmu.c:user_mem_abort",
        "virt/kvm/arm/mmu.c:stage2_unmap_vm",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:uprobe_notify_resume",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:__arm64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__arm64_sys_brk",
        "mm/mprotect.c:__arm64_sys_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__arm64_sys_msync",
        "mm/msync.c:__arm64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492774944,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226592144,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/fault.c:do_page_fault",
        "arch/arm/mm/mmap.c:arch_get_unmapped_area_topdown",
        "arch/arm/mm/mmap.c:arch_get_unmapped_area",
        "kernel/sys.c:prctl_set_mm",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/mincore.c:__se_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__se_sys_msync",
        "mm/msync.c:__se_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:find_mergeable_vma",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:setup_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226592144,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286142144,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/fault.c:__do_page_fault",
        "arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area_topdown",
        "arch/powerpc/mm/mmap.c:radix__arch_get_unmapped_area",
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area",
        "arch/powerpc/mm/book3s64/subpage_prot.c:__se_sys_subpage_prot",
        "arch/powerpc/mm/copro_fault.c:copro_handle_mm_fault",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__se_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__se_sys_msync",
        "mm/msync.c:__se_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286142144,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272749916,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/mm/fault.c:do_page_fault",
        "kernel/sys.c:prctl_set_mm",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/mincore.c:__se_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__se_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__se_sys_brk",
        "mm/mprotect.c:__se_sys_mprotect",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__se_sys_msync",
        "mm/msync.c:__se_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/ksm.c:ksm_do_scan",
        "mm/ksm.c:find_mergeable_vma",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272749916,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581338256,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338256,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281968,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281968,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329456,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329456,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vm_area_struct * find_vma(struct mm_struct * mm, long unsigned int addr)
```

```json
{
  "name": "find_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393536,
      "name": "find_vma",
      "external": true,
      "loc": "mm/mmap.c:2235",
      "file": "mm/mmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown",
        "arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area",
        "arch/x86/mm/mpx.c:mpx_notify_unmap",
        "arch/x86/mm/mpx.c:zap_bt_entries_mapping",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "arch/x86/mm/mpx.c:mpx_enable_management",
        "kernel/sys.c:prctl_set_mm",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/trace/trace_output.c:trace_user_stack_print",
        "kernel/bpf/stackmap.c:stack_map_get_build_id_offset",
        "kernel/events/uprobes.c:handle_swbp",
        "kernel/events/uprobes.c:register_for_each_vma",
        "mm/gup.c:__mm_populate",
        "mm/memory.c:print_vma_addr",
        "mm/memory.c:__access_remote_vm",
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__ia32_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__x64_sys_remap_file_pages",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:__do_munmap",
        "mm/mmap.c:find_extend_vma",
        "mm/mmap.c:find_vma_prev",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_mmap",
        "mm/mmap.c:__ia32_sys_brk",
        "mm/mmap.c:__x64_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:vma_to_resize",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__ia32_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/msync.c:__x64_sys_msync",
        "mm/pagewalk.c:walk_page_range",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/hugetlb.c:huge_pmd_share",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:new_page",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:find_mergeable_vma",
        "mm/migrate.c:do_pages_stat",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hugepage_vma_revalidate",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/frame_vector.c:get_vaddr_frames",
        "mm/hmm.c:hmm_range_fault",
        "fs/exec.c:shift_arg_pages",
        "fs/proc/task_mmu.c:pagemap_pte_hole",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_lookup",
        "fs/proc/base.c:map_files_get_link",
        "fs/proc/base.c:map_files_d_revalidate",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:do_shmat",
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393536,
      "name": "find_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
