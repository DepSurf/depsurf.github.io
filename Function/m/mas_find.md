# Function: <code>mas_find</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * mas_find(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595821136,
      "name": "mas_find",
      "external": true,
      "loc": "lib/maple_tree.c:5994",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/acct.c:acct_collect",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:update_ref_ctr",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/vmscan.c:get_next_vma",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:free_pgtables",
        "mm/memory.c:free_pgtables",
        "mm/mlock.c:apply_mlockall_flags",
        "mm/mlock.c:do_mlock",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:do_mas_munmap",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:do_mas_align_munmap",
        "mm/mmap.c:count_vma_pages_range",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:mbind_range",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_unmap_prep",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595821136,
      "name": "mas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * mas_find(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_find",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596328608,
      "name": "mas_find",
      "external": true,
      "loc": "lib/maple_tree.c:5969",
      "file": "lib/maple_tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/acct.c:acct_collect",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:update_ref_ctr",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/vmscan.c:get_next_vma",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:free_pgtables",
        "mm/memory.c:free_pgtables",
        "mm/mlock.c:apply_mlockall_flags",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:count_vma_pages_range",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:new_folio",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/ksm.c:ksm_disable_merge_any",
        "mm/ksm.c:ksm_enable_merge_any",
        "mm/ksm.c:ksm_del_vmas",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_exit",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_sync",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596328608,
      "name": "mas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void * mas_find(struct ma_state * mas, long unsigned int max)
```

```json
{
  "name": "mas_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597250576,
      "name": "mas_find",
      "external": true,
      "loc": "lib/maple_tree.c:6012",
      "file": "lib/maple_tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vdso/vma.c:map_vdso_once",
        "arch/x86/entry/vdso/vma.c:vdso_join_timens",
        "kernel/fork.c:replace_mm_exe_file",
        "kernel/fork.c:dup_mmap",
        "kernel/fork.c:dup_mmap",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/sched/fair.c:task_numa_work",
        "kernel/acct.c:acct_collect",
        "kernel/bpf/task_iter.c:bpf_iter_task_vma_next",
        "kernel/events/core.c:perf_event_addr_filters_apply",
        "kernel/events/uprobes.c:find_active_uprobe",
        "kernel/events/uprobes.c:update_ref_ctr",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/vmscan.c:get_next_vma",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:free_pgtables",
        "mm/memory.c:free_pgtables",
        "mm/mlock.c:apply_mlockall_flags",
        "mm/mlock.c:do_mlock",
        "mm/mlock.c:apply_vma_lock_flags",
        "mm/mmap.c:mm_drop_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:mm_take_all_locks",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:__do_sys_remap_file_pages",
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:do_vmi_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:do_vmi_align_munmap",
        "mm/mmap.c:__split_vma",
        "mm/mmap.c:count_vma_pages_range",
        "mm/mmap.c:__do_sys_brk",
        "mm/mmap.c:__do_sys_brk",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mprotect.c:do_mprotect_pkey",
        "mm/mremap.c:move_vma",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:__do_sys_set_mempolicy_home_node",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:mpol_rebind_mm",
        "mm/ksm.c:ksm_disable_merge_any",
        "mm/ksm.c:ksm_enable_merge_any",
        "mm/ksm.c:ksm_del_vmas",
        "mm/ksm.c:scan_get_next_rmap_item",
        "mm/ksm.c:unmerge_and_remove_all_rmap_items",
        "mm/userfaultfd.c:mwriteprotect_range",
        "fs/exec.c:shift_arg_pages",
        "fs/exec.c:shift_arg_pages",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_unregister",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release",
        "fs/userfaultfd.c:userfaultfd_event_wait_completion",
        "fs/coredump.c:dump_vma_snapshot",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_next",
        "fs/proc/task_mmu.c:m_start",
        "fs/proc/base.c:proc_map_files_readdir",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt",
        "ipc/shm.c:ksys_shmdt",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_exit",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_sync",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_drop",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write",
        "drivers/base/regmap/regcache-maple.c:regcache_maple_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597250576,
      "name": "mas_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void * mas_find(struct ma_state * mas, long unsigned int max)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
