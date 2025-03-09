# Function: <code>__xchg_case_mb_64</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
u64 __xchg_case_mb_64(u64 x, volatile void * ptr)
```

```json
{
  "name": "__xchg_case_mb_64",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490397316,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_get_dirty_log_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/panic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490669108,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490695196,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_cad_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490766648,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:prctl_set_mm_exe_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490790356,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/umh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490848788,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthreadd",
        "kernel/kthread.c:__kthread_create_on_node"
      ],
      "caller_func": [
        "kernel/kthread.c:kthread"
      ]
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490920616,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_ttwu_pending"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490937256,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/sched/loadavg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/loadavg.c:calc_global_load"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491116476,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/locking/osq_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_unlock",
        "kernel/locking/osq_lock.c:osq_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/rcu/tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491456828,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smp.c:flush_smp_call_function_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491479172,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:do_free_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491497708,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/acct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/acct.c:__arm64_sys_acct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491508268,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/kexec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load",
        "kernel/kexec.c:do_kexec_load"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491511500,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/debug/debug_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/hung_task.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491950160,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/trace/blktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:__blk_trace_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492101664,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/irq_work.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492234284,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:fd_array_map_delete_elem",
        "kernel/bpf/arraymap.c:bpf_fd_array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492247904,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492279780,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/devmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_update_elem",
        "kernel/bpf/devmap.c:dev_map_delete_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492284548,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/cpumap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492290208,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/xskmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/xskmap.c:xsk_map_delete_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492300788,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/bpf/stackmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/stackmap.c:stack_map_delete_elem",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_stackmap_copy",
        "kernel/bpf/stackmap.c:bpf_get_stackid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492335480,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:task_clock_event_read",
        "kernel/events/core.c:task_clock_event_stop",
        "kernel/events/core.c:cpu_clock_event_update",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492394428,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "kernel/events/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/ring_buffer.c:perf_output_begin",
        "kernel/events/ring_buffer.c:perf_output_begin_backward",
        "kernel/events/ring_buffer.c:perf_output_begin_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492547176,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:do_shrink_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492833668,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__purge_vmap_area_lazy",
        "mm/vmalloc.c:free_work"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/swap_state.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492976860,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:free_hpage_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493122440,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493174040,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/page_counter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_counter.c:page_counter_set_max",
        "mm/page_counter.c:propagate_protected_usage",
        "mm/page_counter.c:propagate_protected_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186104,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:swap_max_write",
        "mm/memcontrol.c:memory_max_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493323876,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:delayed_fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493506196,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493523732,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namespace.c:delayed_mntput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493766312,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/eventpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/eventpoll.c:ep_poll_callback",
        "fs/eventpoll.c:ep_poll_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493983312,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/posix_acl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:__forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/proc/kcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494496332,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "fs/ext4/page-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/page-io.c:ext4_end_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "lib/debug_locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496153896,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "lib/generic-radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/generic-radix-tree.c:__genradix_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496356552,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497691980,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498228952,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/xen/events/events_2l.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_2l.c:evtchn_2l_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498403416,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498426988,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/tty/tty_audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_audit.c:tty_audit_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/media/cec/cec-pin.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501768360,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501859724,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sk_setup_caps",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setbindtodevice_locked",
        "net/core/sock.c:sk_dst_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501949992,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_kill_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501956132,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502206356,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502279512,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/skmsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred",
        "net/core/skmsg.c:sk_psock_destroy_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502352660,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_map_prog_update",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:sock_hash_release_progs",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_release_progs",
        "net/core/sock_map.c:sock_map_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502503196,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tcf_set_action_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502565232,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/netfilter/nf_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_buf_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502593780,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_sk_update_pmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502641716,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502660176,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502674784,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502809156,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/tcp_cong.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_cong.c:tcp_set_default_congestion_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502828360,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/datagram.c:ip4_datagram_release_cb",
        "net/ipv4/datagram.c:__ip4_datagram_connect",
        "net/ipv4/datagram.c:__ip4_datagram_connect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502832060,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502843256,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_disconnect",
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502921528,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/af_inet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/af_inet.c:__inet_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503005864,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/ping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ping.c:ping_bind"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503091964,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv4/cipso_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503223716,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/af_inet6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_destroy_sock",
        "net/ipv6/af_inet6.c:inet6_destroy_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503347564,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503365472,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503385784,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/ipv6_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options",
        "net/ipv6/ipv6_sockglue.c:ipv6_update_options"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503495848,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503515028,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/datagram.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/datagram.c:ipv6_recv_rxpmtu",
        "net/ipv6/datagram.c:ipv6_local_rxpmtu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503580068,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/ipv6/calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/calipso.c:calipso_req_delattr",
        "net/ipv6/calipso.c:calipso_req_setattr"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503700504,
      "name": "__xchg_case_mb_64",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:60",
      "file": "net/netlabel/netlabel_calipso.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_ops_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490841144,
      "name": "__xchg_case_mb_64.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446603336503378688,
      "name": "__xchg_case_mb_64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u64 __xchg_case_mb_64(u64 x, volatile void * ptr)
```
</details>
</li>
</ul>
