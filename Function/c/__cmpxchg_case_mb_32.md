# Function: <code>__cmpxchg_case_mb_32</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u32 __cmpxchg_case_mb_32(volatile void * ptr, u32 old, u32 new)
```

```json
{
  "name": "__cmpxchg_case_mb_32",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490403664,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "virt/kvm/kvm_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/kvm_main.c:kvm_make_vcpus_request_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490442128,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:kvm_arch_vcpu_should_kick"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "virt/kvm/arm/vgic/vgic-mmio-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490641872,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:panic",
        "kernel/panic.c:nmi_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490659596,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:wait_task_zombie"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/task_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490863552,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490876068,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/smpboot.c:cpu_report_death",
        "kernel/smpboot.c:cpu_wait_death"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490877828,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/ucount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:dec_ucount",
        "kernel/ucount.c:inc_ucount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490878848,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/kmod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/sched/fair.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491102604,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_poll_work",
        "kernel/sched/psi.c:psi_poll_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491108452,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/locking/mutex.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/locking/osq_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491166316,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/printk/printk_safe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:__printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_log_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491204916,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/irq/chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:irq_chip_pm_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491272540,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_eqs_special_set",
        "kernel/rcu/tree.c:rcu_eqs_special_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491476936,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_module_get",
        "kernel/module.c:__arm64_sys_delete_module"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/acct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491506132,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_kexec"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cgroup/rdma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491716112,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/debug/kdb/kdb_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_io.c:vkdb_printf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491729820,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_param_enable_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491824836,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_record_on",
        "kernel/trace/ring_buffer.c:ring_buffer_record_on",
        "kernel/trace/ring_buffer.c:ring_buffer_record_off",
        "kernel/trace/ring_buffer.c:ring_buffer_record_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491917756,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/trace/trace_functions.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/trace/blktrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/irq_work.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492139620,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_inc_not_zero"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492349916,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_mmap",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/events/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492410136,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:register_for_each_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492429968,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/jump_label.c:static_key_disable_cpuslocked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492449312,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_contig",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_get_entries",
        "mm/filemap.c:find_get_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/page-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492526988,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:deactivate_file_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492555168,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:__isolate_lru_page",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:__remove_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/mmzone.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492716448,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492791484,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/mmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap.c:mmap_region",
        "mm/mmap.c:mmap_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492822544,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492934640,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/frontswap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492998632,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:isolate_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493048708,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:get_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493117204,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:isolate_movable_page",
        "mm/migrate.c:isolate_movable_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493144888,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:deferred_split_scan",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493160532,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186968,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493229284,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:get_hwpoison_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/cleancache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493273384,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/page_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_idle.c:page_idle_get_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493281532,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_range_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493286788,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "mm/memfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memfd.c:memfd_fcntl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493292864,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open",
        "fs/open.c:vfs_truncate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493330272,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/super.c:grab_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493353040,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:kernel_read_file",
        "fs/exec.c:kernel_read_file",
        "fs/exec.c:do_open_execat",
        "fs/exec.c:do_open_execat"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493400768,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/namei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/namei.c:do_last"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493468716,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/dcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dcache.c:d_splice_alias",
        "fs/dcache.c:__d_move",
        "fs/dcache.c:d_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493483532,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:inode_set_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/nsfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/notify/mark.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/eventpoll.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493795604,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_ioctl",
        "fs/userfaultfd.c:userfaultfd_register",
        "fs/userfaultfd.c:userfaultfd_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493804412,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__get_reqs_available"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493851424,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/crypto/keysetup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493898308,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/verity/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/posix_acl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494011148,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/iomap/direct-io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/direct-io.c:iomap_dio_bio_end_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494065148,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:m_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494069748,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_get_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_llseek"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494089572,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/proc/base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:environ_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494131792,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:drop_sysctl_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494166232,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rename",
        "fs/kernfs/dir.c:kernfs_iop_rmdir",
        "fs/kernfs/dir.c:kernfs_iop_mkdir",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494221876,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/balloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494300608,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/ialloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494437260,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_process_freed_data",
        "fs/ext4/mballoc.c:ext4_process_freed_data"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494600260,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:__ext4_grp_locked_error",
        "fs/ext4/super.c:__ext4_grp_locked_error"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fat/dir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fat/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fat/namei_vfat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494913240,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fuse/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dir.c:fuse_do_setattr",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_link",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_rename_common",
        "fs/fuse/dir.c:fuse_unlink",
        "fs/fuse/dir.c:fuse_dir_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/fuse/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "fs/debugfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "security/integrity/ima/ima_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/bio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495859240,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495875532,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495952404,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-rq-qos.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-rq-qos.c:rq_wait_inc_below"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496010480,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/llist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/rhashtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496152968,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/errseq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/errseq.c:errseq_check_and_advance",
        "lib/errseq.c:errseq_check_and_advance",
        "lib/errseq.c:errseq_set",
        "lib/errseq.c:errseq_set"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/genalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496358168,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:__sbq_wake_up",
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496420904,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/irqchip/irq-mvebu-icu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_write_msg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496478684,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/phy/phy-core.c:phy_pm_runtime_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496891212,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/pci/pci-driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497221056,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/rapidio/rio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/rapidio/rio.c:rio_unregister_mport"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497730900,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/amba/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_remove",
        "drivers/amba/bus.c:amba_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498232956,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/xen/events/events_fifo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events",
        "drivers/xen/events/events_fifo.c:__evtchn_fifo_handle_events"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/tty_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498519148,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_console.c:hvc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498537128,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_poll_put_char",
        "drivers/tty/serial/serial_core.c:uart_poll_get_char",
        "drivers/tty/serial/serial_core.c:uart_dtr_rts",
        "drivers/tty/serial/serial_core.c:uart_carrier_raised",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_icount",
        "drivers/tty/serial/serial_core.c:uart_wait_modem_status",
        "drivers/tty/serial/serial_core.c:uart_unthrottle",
        "drivers/tty/serial/serial_core.c:uart_throttle",
        "drivers/tty/serial/serial_core.c:uart_send_xchar",
        "drivers/tty/serial/serial_core.c:uart_flush_buffer",
        "drivers/tty/serial/serial_core.c:uart_chars_in_buffer",
        "drivers/tty/serial/serial_core.c:uart_write_room",
        "drivers/tty/serial/serial_core.c:uart_write",
        "drivers/tty/serial/serial_core.c:uart_put_char",
        "drivers/tty/serial/serial_core.c:uart_shutdown",
        "drivers/tty/serial/serial_core.c:uart_start",
        "drivers/tty/serial/serial_core.c:uart_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498615808,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/serial/8250/8250_dw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dw.c:dw8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498621832,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/serial/8250/8250_mtk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498716668,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/tty/serdev/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serdev/core.c:serdev_device_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498735972,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:credit_entropy_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498863248,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/iommu/iova.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/iova.c:queue_iova"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498963996,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/base/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_link_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499060960,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:pm_runtime_clean_up_links",
        "drivers/base/power/runtime.c:__pm_runtime_disable",
        "drivers/base/power/runtime.c:pm_runtime_barrier",
        "drivers/base/power/runtime.c:__pm_runtime_set_status",
        "drivers/base/power/runtime.c:pm_runtime_get_if_in_use",
        "drivers/base/power/runtime.c:rpm_suspend",
        "drivers/base/power/runtime.c:rpm_get_suppliers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499089548,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:pm_system_cancel_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499494992,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/dma-buf/dma-fence-array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work",
        "drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/dma-buf/dma-fence-chain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499526540,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/scsi/hosts.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/hosts.c:scsi_add_host_with_dma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499893764,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:__spi_pump_messages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499911368,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/spi/spi-omap2-mcspi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499921528,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/loopback.c:loopback_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500013012,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/net/ethernet/freescale/fec_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500183448,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/cdrom/cdrom.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500233068,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hcd_end_port_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500271424,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/usb/core/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/driver.c:usb_autopm_get_interface_async",
        "drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500343120,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/usb/core/hcd-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500711232,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/usb/host/xhci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500879880,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/i2c/busses/i2c-designware-master.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500881008,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500890216,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/i2c/busses/i2c-sprd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500992064,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register",
        "drivers/thermal/thermal_core.c:__thermal_cooling_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501171444,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_alloc_md_mempools",
        "drivers/md/dm.c:dm_get_numa_node",
        "drivers/md/dm.c:dm_get_numa_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501320712,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:dbs_update_util_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501404696,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/mmc/core/sdio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501408296,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/mmc/core/sdio_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sdio_bus.c:sdio_bus_remove",
        "drivers/mmc/core/sdio_bus.c:sdio_bus_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501434196,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503915324,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/firmware/efi/efi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/efi.c:efi_mem_reserve_persistent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501684720,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501762984,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/arm-cci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-cci.c:cci_pmu_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/arm_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/hisilicon/hisi_uncore_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/qcom_l2_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/qcom_l3_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "drivers/perf/xgene_pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501880828,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:sk_dst_check",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sk_receive_skb",
        "net/core/sock.c:__sock_queue_rcv_skb",
        "net/core/sock.c:__sock_queue_rcv_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501905320,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:__copy_skb_header",
        "net/core/skbuff.c:skb_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502035280,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:net_rx_action",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:napi_busy_loop",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_loopback_xmit",
        "net/core/dev.c:dev_fill_metadata_dst",
        "net/core/dev.c:dev_fill_metadata_dst"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502113828,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:__neigh_event_send"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502206196,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_setsockopt",
        "net/core/filter.c:bpf_skb_set_tunnel_key",
        "net/core/filter.c:bpf_skb_set_tunnel_key"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/sock_diag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502284320,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_poll_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/lwtunnel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502354272,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/dst_cache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst_cache.c:dst_cache_set_ip6",
        "net/core/dst_cache.c:dst_cache_set_ip4"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502566408,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/netfilter/nf_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_queue.c:nf_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502591392,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:ip_route_output_key_hash_rcu",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:rt_cache_route",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ipv4_sk_update_pmtu",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/route.c:ip_idents_reserve",
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502611704,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/ip_options.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_options.c:ip_options_rcv_srr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502616944,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502634612,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/ip_sockglue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502682840,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502786872,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:inet_sk_rx_dst_set",
        "net/ipv4/tcp_ipv4.c:tcp_add_backlog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502802816,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/tcp_minisocks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_minisocks.c:tcp_child_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502821104,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_active_disable_ofo_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502862624,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_sendmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502876828,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502885708,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503047336,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503136104,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:__xfrm_route_forward",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid",
        "net/xfrm/xfrm_policy.c:xdst_queue_output",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_policy_queue_process",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create",
        "net/xfrm/xfrm_policy.c:xfrm_bundle_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503177448,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/xfrm/xfrm_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_input.c:xfrm_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503181456,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_output.c:xfrm_output_one",
        "net/xfrm/xfrm_output.c:xfrm_output_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503248368,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:__ip6_make_skb",
        "net/ipv6/ip6_output.c:ip6_setup_cork",
        "net/ipv6/ip6_output.c:ip6_copy_metadata"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503333388,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_route_output_flags",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_pol_route_lookup",
        "net/ipv6/route.c:ip6_create_rt_rcu",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503365272,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_new_sernum"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503488960,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:inet6_sk_rx_dst_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503524500,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/ip6_flowlabel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_opt",
        "net/ipv6/ip6_flowlabel.c:__fl6_sock_lookup",
        "net/ipv6/ip6_flowlabel.c:fl_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503541312,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_cache_report"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503570844,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/fib6_rules.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/fib6_rules.c:fib6_rule_action",
        "net/ipv6/fib6_rules.c:fib6_rule_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503594536,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx4",
        "net/ipv6/seg6_local.c:seg6_lookup_nexthop"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/ip6_icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/ipv6/protocol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "net/xdp/xdp_umem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503805748,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/dec_and_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503806856,
      "name": "__cmpxchg_case_mb_32",
      "external": false,
      "loc": "arch/arm64/include/asm/cmpxchg.h:129",
      "file": "lib/dump_stack.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/dump_stack.c:dump_stack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492339912,
      "name": "__cmpxchg_case_mb_32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
u32 __cmpxchg_case_mb_32(volatile void * ptr, u32 old, u32 new)
```
</details>
</li>
</ul>
