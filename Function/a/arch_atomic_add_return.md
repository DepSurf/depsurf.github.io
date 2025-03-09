# Function: <code>arch_atomic_add_return</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870526,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578931575,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140068,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579161704,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_panic",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169957,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/kernel/cpu/mcheck/mce_intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579374330,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426268,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446198,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463621,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477689,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499512,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__do_sys_kill",
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530695,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641975,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579744485,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579751447,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589272517,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798915,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865663,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579882210,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912911,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_dynticks_momentary_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579944315,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580082725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580156357,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213342,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580222113,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580252864,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580352429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382991,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:register_ftrace_graph",
        "kernel/trace/ftrace.c:profile_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580443024,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580458719,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580463024,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580466296,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580477804,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580496267,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580529120,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580607901,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580628453,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580685792,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580736463,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/bpf/sockmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580824576,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580844548,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848965,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:dev_pagemap_get_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892240,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268148,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581322248,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383832,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581486084,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502902,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525837,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603913,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660058,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:kill_fasync",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696160,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716222,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812347,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043501,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582083760,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100971,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582122746,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582126629,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158687,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/proc/kcore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/kcore.c:read_kcore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174329,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_put_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265861,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361124,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582506552,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601698,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582619374,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735461,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582935671,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004398,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018366,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583123827,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288001,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583366874,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583621925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583796729,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584056998,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584206402,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584966853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585183217,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585195658,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585207953,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585238745,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248603,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585255570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585333169,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585745719,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585829372,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585838402,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585943402,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586129139,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_request_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586176240,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586212945,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586260832,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586279649,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586943725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586967819,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587106821,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587276181,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq",
        "drivers/md/dm.c:dec_pending",
        "drivers/md/dm.c:alloc_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333829,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587342053,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587344853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350162,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587507754,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616858,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587619721,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587626826,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587676933,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587748675,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810865,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587887866,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888857,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:__neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001624,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588018836,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588081306,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588096847,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588107407,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588120238,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588128562,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188546,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588384278,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588404861,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588420023,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539733,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588563012,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588601160,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588686163,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588753394,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588790862,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588842041,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588866370,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588940506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588996069,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589062365,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:159",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870350,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578933111,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_online",
        "arch/x86/events/intel/uncore.c:uncore_event_cpu_offline",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151152,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204436,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579401994,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459692,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579479718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497205,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579511028,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538141,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579566807,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579679607,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579784416,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579794279,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589515653,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579845506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912687,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929986,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976338,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579991403,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580130085,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580204085,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580265977,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580274509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580306115,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/auditsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:audit_set_loginuid",
        "kernel/auditsc.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580408669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580416171,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580498672,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580514290,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580518624,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580522136,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580532980,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:register_ftrace_graph"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580553979,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580586976,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580666173,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580687557,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580757568,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580891328,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908980,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:dev_pagemap_get_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process",
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293941,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:free_vmap_area_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350868,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406440,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468056,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571860,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588742,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690317,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746378,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:kill_fasync",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782512,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802942,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581899339,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582131119,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177888,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195307,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582217178,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582221109,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582269417,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_put_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302789,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365314,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582460272,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607080,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582703442,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721118,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_update_sb_errno",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_mark_journal_empty",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839269,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044215,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583117550,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134565,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240019,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583406369,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485626,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683157,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583726741,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583878229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584139565,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584294210,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585071509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585299952,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585314250,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585326081,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585358057,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585368230,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585374962,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456481,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585878471,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585963509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971376,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586079578,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586271300,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586318528,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355089,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586401296,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586420513,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587104509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128683,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284613,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587456405,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587512165,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587520213,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587523013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587528715,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587688122,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587744154,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587749289,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587756247,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587808229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882771,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946625,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588029066,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588030361,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588160744,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588186292,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588227100,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258202,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588274130,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290767,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588302494,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588307279,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373045,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_defrag"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588574982,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588596429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588612055,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588736005,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588760292,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588804873,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588822446,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588903228,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973586,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589011246,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589065633,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589089785,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589164762,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589219494,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589288061,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870622,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578937400,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163579,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171466,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579217339,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579417434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477405,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497735,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515158,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530617,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555439,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589801,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712510,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579822815,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589974629,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579879658,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579950081,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968354,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580002611,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033196,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580176869,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251403,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_fs_context"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580316855,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333354,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580461595,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580469662,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580555120,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580570110,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580574880,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580578488,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580589311,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580608482,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580611090,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580644144,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580729549,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754709,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580841341,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989066,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006901,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060419,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581461333,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518584,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583571,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682950,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700063,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722150,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813535,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863904,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901360,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581921824,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582185608,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293364,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341023,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358715,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381306,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386662,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433849,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_put_active"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582469141,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533289,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629238,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582779116,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876451,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582894799,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583014309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226455,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304585,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583321925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583426932,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592559,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671722,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583871877,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584069317,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584329783,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584488466,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585275669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585513620,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585525519,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585538004,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571619,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585581831,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585588782,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585672387,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114919,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586206614,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586214578,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314986,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586514981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586561906,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597596,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586645390,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586666289,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587368891,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587392550,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587554069,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587729749,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587786037,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587794101,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587796853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802758,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587967344,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588049958,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588053855,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588060884,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588113701,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588188036,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256177,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588342250,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588343454,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588486568,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588511942,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588563295,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588624045,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588649519,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588665703,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588688484,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588700430,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588705332,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588775012,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588986262,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589007996,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589023896,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589168133,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193236,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589238277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589255502,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589345772,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589416763,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589463063,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589519324,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589544034,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589619791,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589674497,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589743534,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870798,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939880,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166046,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173914,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219627,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579420618,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579503453,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523735,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579541318,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556773,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579581583,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579615941,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579754718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579829707,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/sched/rt.c:tg_set_rt_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860501,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870943,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929823,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579999937,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018162,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052815,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580083916,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580224757,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299531,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580365687,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580382218,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580510507,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580517790,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580602912,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580617262,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580621968,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580625576,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580636399,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580655458,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657378,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690848,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580779844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580805301,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580892381,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043050,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062688,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116195,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581525397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583144,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581648243,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755382,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773519,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795606,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581812508,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886111,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936276,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973776,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994208,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174341,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265430,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392340,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440159,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582457611,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582480218,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582485574,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582568085,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634793,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582730365,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882220,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582983075,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001375,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120501,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332263,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409305,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583427253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583532836,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698719,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583778730,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974773,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584152575,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192021,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584464471,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624050,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413621,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585652347,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585666527,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585678916,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585712649,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722743,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585729646,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585813331,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586262919,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586354726,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586362626,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586463162,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586662984,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586709010,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586745036,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586792942,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586813601,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587570731,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587594582,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587757397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587934101,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587990773,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587998821,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588174480,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588236972,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588253352,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588259823,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588266788,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588319397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393188,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588461329,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588548698,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588549902,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588694248,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588703707,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588720518,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588780383,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846157,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871887,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588888663,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588912612,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588924318,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588929220,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998612,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589210694,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589232552,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248456,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392341,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589418676,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589463605,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480446,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569980,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589641003,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687387,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589743436,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589768114,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589844031,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589898769,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578874910,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578945176,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579180737,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579190302,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239708,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450856,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:ioremap_trace_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579531725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555252,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572988,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579588229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579647077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788916,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579899145,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579912895,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591218245,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579972718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580048421,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:misrouted_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065332,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109294,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_boot_init_percpu_data",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580142889,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580291653,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580439747,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580459373,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597339,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603776,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_profile_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580700464,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580715200,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:get_free_elt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722194,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580725160,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580738074,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756388,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:alloc_retstack_tasklist"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768532,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798125,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898276,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040275,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581255720,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300019,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328702,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:put_devmap_managed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__unpin_devmap_managed_user_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733445,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795192,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581865491,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018670,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032759,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108202,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:de_thread",
        "fs/exec.c:__do_sys_uselib",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582166304,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown_ex",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206640,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582228408,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582339377,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411301,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539168,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_cancel_files",
        "fs/io_uring.c:__io_cqring_fill_event",
        "fs/io_uring.c:io_cqring_overflow_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679017,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582733839,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582750245,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778826,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784698,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582831587,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582838458,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582876389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943692,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583038763,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583194504,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583299363,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_free_reserved",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326175,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440405,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665950,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750672,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583783933,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583882227,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/selinux/ss/services.c:security_sid_to_context_core",
        "security/selinux/ss/services.c:security_sidtab_hash_stats",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067648,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169274,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584362101,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584586709,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584616986,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585028428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585306837,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124629,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586379100,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586391759,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586410088,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441785,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586451918,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461534,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544003,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030564,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587126870,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587132594,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587463376,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587514480,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587552519,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587596286,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587659857,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588430555,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452662,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588605461,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588786533,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588844805,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588852933,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588856073,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589038893,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589109324,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132942,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589138544,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589146383,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589256739,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589327633,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589399592,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589404718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589564848,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:proto_down_show",
        "net/core/net-sysfs.c:group_show",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_show",
        "net/core/net-sysfs.c:gro_flush_timeout_show",
        "net/core/net-sysfs.c:tx_queue_len_show",
        "net/core/net-sysfs.c:flags_show",
        "net/core/net-sysfs.c:mtu_show",
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show",
        "net/core/net-sysfs.c:name_assign_type_show",
        "net/core/net-sysfs.c:link_mode_show",
        "net/core/net-sysfs.c:type_show",
        "net/core/net-sysfs.c:ifindex_show",
        "net/core/net-sysfs.c:addr_len_show",
        "net/core/net-sysfs.c:addr_assign_type_show",
        "net/core/net-sysfs.c:dev_port_show",
        "net/core/net-sysfs.c:dev_id_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589570667,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589588206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589649285,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589730151,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758431,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589773775,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589800772,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589813550,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/ematch.c:tcf_em_lookup",
        "net/sched/ematch.c:tcf_em_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589818899,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922511,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589958120,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590184246,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_v4_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590207160,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590221356,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_format_neigh_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590385973,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590404412,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590453544,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590470974,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590563797,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590648696,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590695527,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590761626,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590787720,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590870505,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590929841,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590998238,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591139685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578946923,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579176929,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186014,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_storm_detect",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233660,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579448120,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:ioremap_trace_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536516,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_task_continued",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579554748,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579568261,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597349,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627605,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579780468,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:uclamp_sync_util_min_rt_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579893865,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:init_overlap_sched_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906367,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591712785,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960510,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031285,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:poll_spurious_irqs",
        "kernel/irq/spurious.c:misrouted_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047098,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580091534,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_boot_init_percpu_data",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_is_idle_cpu",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120121,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_send_signals",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580275077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580427727,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580447869,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587355,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_profile_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580691312,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580704672,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:get_free_elt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711554,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714632,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727034,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756964,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786141,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892532,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048878,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265018,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297768,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344019,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369851,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:put_devmap_managed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781349,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581843096,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910371,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043956,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs_file",
        "mm/memory-failure.c:collect_procs_anon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066686,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582153658,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:de_thread",
        "fs/exec.c:__do_sys_uselib",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212874,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown_ex",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254112,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582390865,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582465397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748777,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582805567,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582822725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582852122,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858714,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582904339,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582911210,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582949253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018108,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114560,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583155086,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296044,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414659,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_free_reserved",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441935,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583787422,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872144,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584186129,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584288394,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584478965,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584705253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735818,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585176844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585380425,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585463461,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586244341,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586392442,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586496928,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506150,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_array_rearm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586522888,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586556297,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566398,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tiocsctty",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586575838,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654787,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587115660,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587212006,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587217647,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587531169,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587580813,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587619063,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587662430,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587720801,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588462731,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588482870,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628597,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588804997,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588860565,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588868309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588871225,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_main_kobj_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589111084,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589137712,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589145327,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589255875,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589326945,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589400536,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589405582,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589572672,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:proto_down_show",
        "net/core/net-sysfs.c:group_show",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_show",
        "net/core/net-sysfs.c:gro_flush_timeout_show",
        "net/core/net-sysfs.c:tx_queue_len_show",
        "net/core/net-sysfs.c:flags_show",
        "net/core/net-sysfs.c:mtu_show",
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show",
        "net/core/net-sysfs.c:name_assign_type_show",
        "net/core/net-sysfs.c:link_mode_show",
        "net/core/net-sysfs.c:type_show",
        "net/core/net-sysfs.c:ifindex_show",
        "net/core/net-sysfs.c:addr_len_show",
        "net/core/net-sysfs.c:addr_assign_type_show",
        "net/core/net-sysfs.c:dev_port_show",
        "net/core/net-sysfs.c:dev_id_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589580085,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589599886,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589673189,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589793007,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589808767,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836548,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589849822,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/ematch.c:tcf_em_lookup",
        "net/sched/ematch.c:tcf_em_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589855140,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589963071,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998936,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590233417,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_v4_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257816,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590273164,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_format_neigh_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590443541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590462252,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590508571,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590529310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590623717,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_call_ra_chain",
        "net/ipv6/ip6_output.c:ip6_call_ra_chain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590708792,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590756085,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590821002,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590847043,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590931817,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591014428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591062910,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591223925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870830,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578951819,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184401,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193673,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233383,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579450718,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579517661,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579540525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579559356,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579573765,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602821,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579634149,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579788580,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579902268,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579915391,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591660229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963134,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032481,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047826,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580093005,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init_one",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_is_idle_cpu",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123625,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298234,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580432159,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451773,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580590347,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580601308,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580695568,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580710466,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717824,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580719389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580731935,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580760209,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791613,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895780,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063121,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283722,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315336,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363107,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392779,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:put_devmap_managed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581756931,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808901,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581873928,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070190,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092574,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178026,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:de_thread",
        "fs/exec.c:__do_sys_uselib",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237865,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280016,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582302344,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418225,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492373,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582588189,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777291,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834383,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582851189,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582880284,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886922,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582932145,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938650,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582976709,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583043807,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140280,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583155437,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583319596,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437507,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_free_reserved",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583464127,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577413,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583811558,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583898304,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583933277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584212871,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584322234,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584513685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584612004,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584733465,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584763930,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584829435,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585058540,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265449,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343589,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586118981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586276682,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586380208,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586390843,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586408533,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586441260,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586460750,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586538686,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587001932,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587100662,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587107233,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587413424,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587464573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587499360,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587542153,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587599953,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587791372,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588345243,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588364454,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588690693,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588747605,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588755237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588758041,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589000508,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589021918,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589027807,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589035423,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589157283,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589222657,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589297736,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589302206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589471712,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:proto_down_show",
        "net/core/net-sysfs.c:group_show",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_show",
        "net/core/net-sysfs.c:gro_flush_timeout_show",
        "net/core/net-sysfs.c:tx_queue_len_show",
        "net/core/net-sysfs.c:flags_show",
        "net/core/net-sysfs.c:mtu_show",
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show",
        "net/core/net-sysfs.c:name_assign_type_show",
        "net/core/net-sysfs.c:link_mode_show",
        "net/core/net-sysfs.c:type_show",
        "net/core/net-sysfs.c:ifindex_show",
        "net/core/net-sysfs.c:addr_len_show",
        "net/core/net-sysfs.c:addr_assign_type_show",
        "net/core/net-sysfs.c:dev_port_show",
        "net/core/net-sysfs.c:dev_id_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589487953,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589662188,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589697087,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589713439,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589741716,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589755198,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/ematch.c:tcf_em_lookup",
        "net/sched/ematch.c:tcf_em_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589760693,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589877804,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589912942,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590147257,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_v4_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171576,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590187884,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_format_neigh_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590368789,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590388108,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590434555,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590454590,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590563926,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590632728,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590682807,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590748074,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590861364,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590947337,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590993678,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591173173,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871726,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578962203,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218449,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228905,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272052,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_move_group_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579515710,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589373,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579613019,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_stopped",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579631932,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579648709,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677973,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710677,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__do_sys_getpriority",
        "kernel/sys.c:__do_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579884123,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580018361,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:get_group",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580037359,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580075669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/core_sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592833957,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092906,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580165009,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592775695,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_dynticks_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266355,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580451194,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580596223,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580616925,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580761211,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580772412,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872320,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580888435,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896559,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898279,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914025,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944145,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977485,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296807,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527754,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581560584,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610915,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642456,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:put_devmap_managed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582094727,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165288,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582238476,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:__kfence_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384238,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405390,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582436147,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582495434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:search_binary_handler",
        "fs/exec.c:de_thread",
        "fs/exec.c:__do_sys_uselib",
        "fs/exec.c:__do_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582556654,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582598064,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:ihold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582621384,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741041,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806869,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582905725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583104507,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166975,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184293,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213900,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220650,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583266865,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273770,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583312309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381084,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480755,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_seq_structs_summary_stop",
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663148,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583759279,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/fast_commit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/fast_commit.c:ext4_fc_mark_ineligible"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583786934,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_free_reserved",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583817503,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_fc_end_commit_fallback",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583935685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584174598,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584262208,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584297565,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584598231,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584709370,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924901,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585025559,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__do_sys_ioprio_get",
        "block/ioprio.c:__do_sys_ioprio_set",
        "block/ioprio.c:__do_sys_ioprio_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585161177,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585192634,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/keyslot-manager.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585248086,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585504780,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721529,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585802693,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586618853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586789338,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/xen/events/events_base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/events/events_base.c:__xen_evtchn_do_upcall"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586903980,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917166,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586935317,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586967468,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979514,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586987758,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587077102,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587568808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_report_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587672702,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587695473,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587985828,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588032141,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588075708,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588120731,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588184577,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589004251,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589028294,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589186629,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589378725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589438981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589446693,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589449497,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589715564,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589737502,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589743391,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589751967,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589877203,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589944753,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590025816,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590030238,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590209008,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:proto_down_show",
        "net/core/net-sysfs.c:group_show",
        "net/core/net-sysfs.c:napi_defer_hard_irqs_show",
        "net/core/net-sysfs.c:gro_flush_timeout_show",
        "net/core/net-sysfs.c:tx_queue_len_show",
        "net/core/net-sysfs.c:flags_show",
        "net/core/net-sysfs.c:mtu_show",
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show",
        "net/core/net-sysfs.c:name_assign_type_show",
        "net/core/net-sysfs.c:link_mode_show",
        "net/core/net-sysfs.c:type_show",
        "net/core/net-sysfs.c:ifindex_show",
        "net/core/net-sysfs.c:addr_len_show",
        "net/core/net-sysfs.c:addr_assign_type_show",
        "net/core/net-sysfs.c:dev_port_show",
        "net/core/net-sysfs.c:dev_id_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590215887,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590228684,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590420121,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590455023,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590471215,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590500516,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590514350,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/ematch.c:tcf_em_lookup",
        "net/sched/ematch.c:tcf_em_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590519941,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590641660,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_idents_reserve"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590679390,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590696853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590927577,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_send_hdrinc",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_v4_input"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590952312,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590968839,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_format_neigh_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591161461,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591182380,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591235643,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591257102,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591375386,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591446601,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591498775,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591561860,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc",
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:ipv6_raw_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591691350,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591765231,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591831910,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592026693,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578868671,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972859,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594662447,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279848,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599390,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580175723,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580216539,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:__raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irq",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_unlock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580311274,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580329273,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594673105,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_dynticks_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580476014,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580822249,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989905,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581102832,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581123370,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130333,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133889,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151209,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182039,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220714,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594129,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875688,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914412,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971123,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059866,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582533708,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710196,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:__kfence_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936965,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582953155,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583129891,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:ihold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583360821,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583570889,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:mb_cache_shrink",
        "fs/mbcache.c:mb_cache_entry_delete_or_get",
        "fs/mbcache.c:mb_cache_entry_delete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583586250,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583658048,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583678933,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583770025,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777642,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583819573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055469,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295552,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584338911,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584515653,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584875023,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585246694,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585628869,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585712206,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585899545,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585932137,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594108073,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_sq_thread_unpark",
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:__io_arm_poll_handler",
        "io_uring/io_uring.c:io_poll_check_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586089798,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586653389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892276,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586990946,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883285,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588195172,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588214359,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588263049,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588382233,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869589,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_drop_usage_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588901088,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589019615,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589343763,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589392540,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589447831,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589501435,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589567649,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590441261,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590467435,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590645477,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590854469,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590917013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590925525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590928392,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591223364,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591240509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591254025,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591264691,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591396237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591488097,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591567017,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591595951,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591792272,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591806930,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592018194,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592141703,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592266053,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592307199,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592325122,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592569884,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592577628,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592922014,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593038627,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593122250,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593252851,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593477503,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593546310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593793717,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578875151,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578991003,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596396895,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712062,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803442,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836357,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:make_task_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580356955,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580409534,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:__raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irq",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_unlock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580524506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545121,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656406,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_cpu_starting",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580734162,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581108681,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287456,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581411200,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581433434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581445217,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464441,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504522,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539242,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303480,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309947,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596408639,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_kernel_exit_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349564,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405283,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582532152,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875606,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583048828,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583235966,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:__kfence_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583493077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583510723,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699363,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:ihold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583944277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584173126,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584189999,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584264272,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287493,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584387369,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395786,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584441781,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584687787,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584943952,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584988159,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585580863,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585980422,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586492446,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-mq-tag.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:__blk_mq_tag_idle",
        "block/blk-mq-tag.c:__blk_mq_tag_busy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586687401,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586723465,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586818397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_thread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586827738,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_poll_check_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586834466,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "io_uring/cancel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587072913,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039960,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588158274,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231669,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589598692,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589622647,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589676777,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589806159,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589939682,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590377189,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_drop_usage_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590414272,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590547059,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590910635,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590965324,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591025463,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591085373,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591161729,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592080573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592111067,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592310133,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592545989,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592615205,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592625429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592629144,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592969460,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592992749,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593008681,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593020338,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593161183,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593257841,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593346089,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593376975,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593586128,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593602754,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593824933,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593965598,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594101505,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594143728,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594162367,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_append_data"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594431451,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594449132,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594803102,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594930483,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595018506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595154739,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595398031,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595467974,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595736853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595748489,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:163",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug",
        "lib/bug.c:report_bug"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578873135,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578990267,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596927855,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579353661,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579725342,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579851570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579885381,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:make_task_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424539,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580478302,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:__raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irq",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_unlock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580597246,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580618578,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732517,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_cpu_starting",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580814258,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581200329,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381392,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581506176,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581530266,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538109,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542273,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582089,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622638,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658634,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504264,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582510801,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596940735,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_kernel_exit_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582552414,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611299,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582735573,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583091320,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap",
        "mm/rmap.c:page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583257404,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455502,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:__kfence_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583708053,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583725619,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583917235,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:ihold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584167605,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584400966,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584417583,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584494560,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584615685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584624218,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584670581,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584912957,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172224,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585216191,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585414661,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811034,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586212966,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586646453,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586946149,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586986361,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587084813,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_thread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587094532,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_poll_check_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587101202,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/cancel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332216,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588314600,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588433794,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589528389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589902015,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589926167,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589981385,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590110931,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590248962,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590697621,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_drop_usage_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590733808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875171,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591253988,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591317916,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591379287,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591442125,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591521329,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592503293,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592534811,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592736581,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592977237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593045797,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593056037,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593059800,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593419828,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593444205,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593460201,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593628303,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593715841,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593839135,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594059152,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_release_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594076140,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594199493,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594342506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594488369,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594530785,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594557673,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594821161,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594840860,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595194766,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595321962,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595411916,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595549981,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595793657,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595975050,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596262837,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596272793,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug",
        "lib/bug.c:report_bug"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578895407,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579015147,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister",
        "arch/x86/events/intel/uncore.c:uncore_pci_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597853583,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_start",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579889378,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579921397,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:make_task_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580484154,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_autogroup_create_attach",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:get_group",
        "kernel/sched/build_utility.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580538126,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:__raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irq",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_unlock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661758,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580683474,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817015,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcutree_report_cpu_starting",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903650,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/module/main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581306417,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434810,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/watchdog.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watchdog.c:watchdog_timer_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581489088,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581617664,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581642234,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/tracing_map.c:__tracing_map_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650253,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_no_repeats_trace_call",
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654631,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup",
        "kernel/trace/trace_sched_wakeup.c:func_prolog_preempt_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694441,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581736078,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774634,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:clear_event_triggers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600263,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:account_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582679345,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/events/hw_breakpoint.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597867327,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/context_tracking.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/context_tracking.c:ct_kernel_exit_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722990,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "kernel/watch_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/watch_queue.c:add_watch_to_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782867,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582903189,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:reclaim_throttle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281725,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:folio_remove_rmap_pmd",
        "mm/rmap.c:folio_remove_rmap_ptes",
        "mm/rmap.c:folio_add_file_rmap_pmd",
        "mm/rmap.c:folio_add_file_rmap_ptes",
        "mm/rmap.c:folio_add_anon_rmap_pmd",
        "mm/rmap.c:folio_add_anon_rmap_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491118,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583648750,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:__kfence_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583908405,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583926371,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "mm/bootmem_info.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/bootmem_info.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583930570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/open.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/open.c:do_dentry_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583967935,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/file_table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/file_table.c:__fput"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584123011,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino",
        "fs/inode.c:ihold"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584381765,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584621686,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/mbcache.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/mbcache.c:mb_cache_destroy",
        "fs/mbcache.c:__entry_find",
        "fs/mbcache.c:mb_cache_entry_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638399,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584717520,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584748197,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_put_link",
        "fs/proc/inode.c:proc_reg_open",
        "fs/proc/inode.c:proc_reg_get_unmapped_area",
        "fs/proc/inode.c:proc_reg_mmap",
        "fs/proc/inode.c:proc_reg_compat_ioctl",
        "fs/proc/inode.c:proc_reg_unlocked_ioctl",
        "fs/proc/inode.c:proc_reg_poll",
        "fs/proc/inode.c:proc_reg_write",
        "fs/proc/inode.c:proc_reg_read",
        "fs/proc/inode.c:proc_reg_read_iter",
        "fs/proc/inode.c:proc_reg_llseek",
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584847738,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/kernfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set",
        "fs/kernfs/inode.c:kernfs_vfs_user_xattr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584856714,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584903333,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585145873,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ext4/mballoc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_regular_allocator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585404992,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ext4/xattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_inode_cache_find",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_xattr_release_block",
        "fs/ext4/xattr.c:ext4_evict_ea_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449151,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:stop_this_handle",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585649557,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586059450,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586465542,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_learning_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874496,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_freeze"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586917413,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587226581,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587268105,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "block/blk-crypto-profile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587364237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/sqpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/sqpoll.c:io_sq_thread_unpark"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587373985,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/poll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/poll.c:io_poll_check_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587380898,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/cancel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_sync_cancel",
        "io_uring/cancel.c:io_async_cancel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587409525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "io_uring/waitid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/waitid.c:io_waitid",
        "io_uring/waitid.c:io_waitid_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615608,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597964985,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "lib/closure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/closure.c:__closure_sync",
        "lib/closure.c:__closure_wake_up",
        "lib/closure.c:closure_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607482,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588730450,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589836885,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_alloc",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590239813,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590257998,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/regulator/event.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/event.c:reg_generate_netlink_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590264455,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/reset/core.c:reset_control_deassert",
        "drivers/reset/core.c:reset_control_assert",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_rearm",
        "drivers/reset/core.c:reset_control_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590320105,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590450259,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590589954,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591059477,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/power/runtime.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:rpm_drop_usage_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591095776,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591218959,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591601208,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready",
        "drivers/scsi/scsi_lib.c:scsi_target_queue_ready"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591666428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591729815,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591792269,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591867387,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/ata/libata-sata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:ata_sas_port_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592173047,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593247789,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593279338,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593484533,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593727221,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593797541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593807829,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593811688,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs",
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594165780,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594190525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/devfreq/devfreq.c:devfreq_resume_device",
        "drivers/devfreq/devfreq.c:devfreq_suspend_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594207192,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594403615,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:msg_zerocopy_realloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594495505,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594620719,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594849950,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:page_pool_return_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594870777,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594996709,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_alloc_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595142092,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595291217,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:__ip_select_ident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595333521,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595360329,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_append_data",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595632472,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595650924,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/igmp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596035326,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/xfrm/xfrm_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596162280,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596253612,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_gc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596392701,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:rawv6_send_hdrinc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596644301,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_snd",
        "net/packet/af_packet.c:tpacket_fill_skb",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596837386,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597145493,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597157529,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:83",
      "file": "lib/bug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/bug.c:report_bug",
        "lib/bug.c:report_bug"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int arch_atomic_add_return(int i, atomic_t * v)
```

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503949728,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/insn.c:aarch64_insn_patch_text_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490256652,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "arch/arm64/kernel/cpu_errata.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490440560,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "virt/kvm/arm/arm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/arm.c:init_hyp_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490726492,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491057752,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491069692,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491192440,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491220828,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491267764,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_enter"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init"
      ]
    },
    {
      "addr": 18446603336491648144,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491798184,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491901216,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491917792,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491925820,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491927284,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491938756,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491971380,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492001584,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492121800,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_prog_add",
        "kernel/bpf/syscall.c:bpf_map_inc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492221356,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492397924,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492425456,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492824192,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_anon_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492954128,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493129636,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493209172,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493485224,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493729952,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493830944,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493991508,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494052680,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494071616,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494213832,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494652876,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494829920,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495164640,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495492152,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496010192,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496883776,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_bus_find_domain_nr",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497692476,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498018424,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/dma/of-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498314156,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498335516,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498683276,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/tty/serial/msm_serial.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/msm_serial.c:msm_serial_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498877720,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/iommu/arm-smmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/arm-smmu.c:arm_smmu_attach_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499083936,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499196828,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499333184,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499563396,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499624368,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499663836,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499719360,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499738424,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500717888,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500738536,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500945872,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/power/reset/vexpress-poweroff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/reset/vexpress-poweroff.c:_vexpress_register_restart_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501170428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501237256,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501245928,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501248268,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501476832,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:_local_event_register",
        "drivers/firmware/arm_sdei.c:_local_event_unregister",
        "drivers/firmware/arm_sdei.c:_ipi_event_disable",
        "drivers/firmware/arm_sdei.c:_local_event_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501525844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/firmware/arm_scmi/clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501694540,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501716024,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501719408,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336501726388,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501908780,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501997788,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502116976,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502266036,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502286092,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502349316,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502415568,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502606204,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502854844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503146152,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503634856,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503704540,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/arm64/include/asm/atomic.h:52",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491254648,
      "name": "arch_atomic_add_return",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870798,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939880,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166398,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174170,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218475,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579416458,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477117,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497399,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514982,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579533077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579557887,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579592245,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730638,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579832853,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579843263,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589804213,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579901471,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579968673,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579986898,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580021551,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580052652,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580193557,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580268331,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334487,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580351018,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580479307,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580486590,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580571712,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580586062,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580590768,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594376,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605199,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580624258,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580626178,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580659648,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580748644,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580774101,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580861181,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581011898,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031536,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085043,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581494133,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581551880,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616979,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724118,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581742255,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764342,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781244,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854847,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905008,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942512,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962944,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071405,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234166,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361076,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408895,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426347,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448954,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582454310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582501306,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582536821,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603529,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699101,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582850956,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951811,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582970111,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583300999,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583378041,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583395989,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501572,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667455,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747466,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583943509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584121311,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584160757,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584433223,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584576210,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585413339,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585427551,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585439940,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585473673,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585483767,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585490670,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585574323,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586026247,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586116614,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124514,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192986,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586353464,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586399490,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586435516,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586514054,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586551550,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586572177,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587263755,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587287398,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587398341,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587565077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587621749,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587629797,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587632549,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587793952,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587848668,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587865048,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587871519,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587878484,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587923045,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587999972,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588068113,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588155434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588156638,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588300984,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588310443,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588327254,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588386767,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588452541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588478271,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588495047,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518996,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588530702,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588535604,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588604996,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588817078,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588838936,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588854776,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588998293,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589023044,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589067973,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589084814,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589174348,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589245371,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291755,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589347804,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589372482,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589448399,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589503137,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589571806,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578864526,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578936856,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097998,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106154,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153307,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579345594,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426279,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579443782,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461845,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579486553,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579520885,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659486,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579736459,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/sched/rt.c:tg_set_rt_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579778031,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589526581,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579836895,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906497,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579924674,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579962783,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579997964,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580140997,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580215829,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281751,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298186,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426443,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580432195,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580518064,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580532686,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580537365,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541912,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580551505,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580570514,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580572418,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605856,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580694836,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720277,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580807309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922795,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958026,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977616,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032227,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436373,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493528,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558307,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662918,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680879,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702966,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719404,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789604,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842612,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880096,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900512,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582008957,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080517,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171926,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582298782,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582346591,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363515,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386122,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391478,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582438538,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582473989,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582540697,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582636269,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582788108,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888963,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582907263,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026389,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583238135,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315145,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583333077,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583438628,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583604511,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684522,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880453,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584056975,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584096021,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584368327,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504370,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585283419,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585297599,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585309972,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585343689,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585353665,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585360510,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585439523,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585872199,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585969122,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586012266,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586194792,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586249013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_transport_fc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_transport_fc.c:fc_host_fpin_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586275746,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586311772,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586382630,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/nvme/host/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/pci.c:nvme_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586420126,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586440753,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587032091,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587055830,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587166549,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333157,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587389765,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587397813,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587400533,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587497376,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587565509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/hv/channel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/channel.c:vmbus_establish_gpadl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587591848,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587598319,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587638901,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587713060,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781201,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587868266,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587869470,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588013800,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588023227,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039921,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588099455,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165229,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190271,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588207047,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588230996,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588242702,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588247604,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588316980,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588529014,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550872,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588566712,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588721349,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588746100,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588793013,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588809854,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588899340,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588970363,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589016747,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589072796,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589097474,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589173391,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589229201,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589296382,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578870734,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578939816,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165966,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173834,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219547,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579416378,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477037,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:walk_process_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497319,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_wait",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_consider_task",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:wait_task_zombie",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:mm_update_next_owner",
        "kernel/exit.c:is_current_pgrp_orphaned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514902,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/resource.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/resource.c:iomem_is_exclusive",
        "kernel/resource.c:iomem_map_sanity_check",
        "kernel/resource.c:lookup_resource",
        "kernel/resource.c:region_intersects",
        "kernel/resource.c:find_next_iomem_res",
        "kernel/resource.c:r_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530357,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:ptrace_check_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555167,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:exit_signals",
        "kernel/signal.c:get_signal",
        "kernel/signal.c:do_signal_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:ptrace_stop",
        "kernel/signal.c:kill_pgrp",
        "kernel/signal.c:kill_something_info",
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:do_prlimit",
        "kernel/sys.c:__ia32_sys_getpriority",
        "kernel/sys.c:__x64_sys_getpriority",
        "kernel/sys.c:__ia32_sys_setpriority",
        "kernel/sys.c:__x64_sys_setpriority"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716286,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:normalize_rt_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579790075,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/rt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/rt.c:sched_rt_handler",
        "kernel/sched/rt.c:tg_set_rt_bandwidth"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579820869,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831311,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590247621,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579890095,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/power/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/process.c:thaw_kernel_threads",
        "kernel/power/process.c:thaw_processes",
        "kernel/power/process.c:try_to_freeze_tasks",
        "kernel/power/process.c:try_to_freeze_tasks"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579960209,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579978434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013087,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_momentary_dyntick_idle",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580044188,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/livepatch/transition.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/livepatch/transition.c:klp_force_transition",
        "kernel/livepatch/transition.c:klp_reverse_transition",
        "kernel/livepatch/transition.c:klp_init_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/livepatch/transition.c:klp_complete_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185029,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580259579,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325735,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:pidns_for_children_get",
        "kernel/pid_namespace.c:reboot_pid_ns",
        "kernel/pid_namespace.c:zap_pid_ns_processes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580342266,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580470555,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/tracepoint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/tracepoint.c:syscall_unregfunc",
        "kernel/tracepoint.c:syscall_regfunc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580477838,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580562960,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580577310,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580582016,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580585624,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580596447,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580615506,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/fgraph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/fgraph.c:start_graph_tracing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617426,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580650896,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580739892,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_uprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_uprobe.c:uprobe_perf_filter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765349,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580852429,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003098,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022736,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076243,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485445,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581543192,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608291,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715430,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733567,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:collect_procs",
        "mm/memory-failure.c:collect_procs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755654,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zsmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_free",
        "mm/zsmalloc.c:zs_unmap_object"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772556,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846159,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:de_thread",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__ia32_sys_uselib",
        "fs/exec.c:__x64_sys_uselib",
        "fs/exec.c:__x64_sys_uselib"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581896324,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fcntl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigurg",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:send_sigio",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:do_fcntl",
        "fs/fcntl.c:f_getown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933824,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581954224,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/filesystems.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__get_fs_type",
        "fs/filesystems.c:filesystems_proc_show",
        "fs/filesystems.c:fs_maxindex",
        "fs/filesystems.c:fs_name",
        "fs/filesystems.c:fs_index",
        "fs/filesystems.c:get_filesystem_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582062685,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/fs_struct.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs_struct.c:chroot_fs_refs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582133557,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224646,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351556,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582399375,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582416827,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/generic.c:__proc_create",
        "fs/proc/generic.c:proc_lookup_de",
        "fs/proc/generic.c:proc_lookup_de"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582444790,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/array.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/array.c:get_children_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491786,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582527301,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593641,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/extents_status.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/extents_status.c:ext4_es_delayed_clu",
        "fs/ext4/extents_status.c:ext4_is_pending",
        "fs/ext4/extents_status.c:ext4_es_lookup_extent",
        "fs/ext4/extents_status.c:ext4_es_scan_clu",
        "fs/ext4/extents_status.c:ext4_es_scan_range",
        "fs/ext4/extents_status.c:ext4_es_find_extent_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582688957,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_setattr",
        "fs/ext4/inode.c:__ext4_iget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582839836,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_sync_fs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940419,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_begin_ordered_truncate",
        "fs/jbd2/transaction.c:jbd2_journal_stop",
        "fs/jbd2/transaction.c:jbd2__journal_restart",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:start_this_handle",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:wait_transaction_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582958719,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:jbd2_journal_errno",
        "fs/jbd2/journal.c:jbd2_journal_get_log_tail",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_complete_transaction",
        "fs/jbd2/journal.c:jbd2_transaction_committed",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:jbd2_log_wait_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit",
        "fs/jbd2/journal.c:__jbd2_journal_force_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583077845,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285031,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/keys/keyring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/keys/keyring.c:find_keyring_by_name"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583361817,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583379765,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/hooks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485348,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/ss/services.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/ss/services.c:security_read_policy",
        "security/selinux/ss/services.c:security_netlbl_sid_to_secattr",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:selinux_audit_rule_match",
        "security/selinux/ss/services.c:selinux_audit_rule_init",
        "security/selinux/ss/services.c:security_policycap_supported",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_permissions",
        "security/selinux/ss/services.c:security_get_classes",
        "security/selinux/ss/services.c:security_net_peersid_resolve",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_get_bool_value",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_policydb_len",
        "security/selinux/ss/services.c:security_compute_av_user",
        "security/selinux/ss/services.c:security_compute_av",
        "security/selinux/ss/services.c:security_compute_xperms_decision",
        "security/selinux/ss/services.c:security_bounded_transition"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651231,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731242,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_iint_find"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583927269,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584105071,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584144517,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584416135,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584574210,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585364021,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585602747,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585616927,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585629316,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_io.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585663049,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585673143,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_jobctrl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:tty_signal_session_leader",
        "drivers/tty/tty_jobctrl.c:tty_open_proc_set_tty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585680046,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/sysrq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/sysrq.c:send_sig_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585763731,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586212935,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586302694,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586310594,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586411130,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586610952,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586663570,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586699596,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586747502,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586768161,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587521979,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587545830,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587713541,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587890245,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946917,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587954965,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587957717,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588129008,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/leds/led-triggers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-triggers.c:led_trigger_blink_oneshot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588190408,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588196879,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588203844,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256453,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588331748,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588399889,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588487258,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588488462,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_seq_stop",
        "net/core/neighbour.c:neigh_for_each",
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588632808,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:operstate_show",
        "net/core/net-sysfs.c:address_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588642267,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588659078,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588718943,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588784717,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588810447,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/sch_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/sch_api.c:qdisc_lookup_ops",
        "net/sched/sch_api.c:qdisc_get_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588827223,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_proto_lookup_ops"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588851172,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/act_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/act_api.c:tc_lookup_action",
        "net/sched/act_api.c:tc_lookup_action_n"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588862878,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/sched/ematch.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588867780,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_getsockopt",
        "net/netlink/af_netlink.c:netlink_set_err",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered",
        "net/netlink/af_netlink.c:netlink_getname",
        "net/netlink/af_netlink.c:netlink_bind",
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_create",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588922273,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netfilter/nfnetlink_log.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nfnetlink_log.c:__build_packet_message"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589041172,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589253254,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/raw.c:raw_seq_stop",
        "net/ipv4/raw.c:raw_icmp_error",
        "net/ipv4/raw.c:raw_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275112,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589291016,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_seq_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589434677,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_vif_seq_stop",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ipmr_get_route",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ip_mr_input",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_compat_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:ipmr_ioctl",
        "net/ipv4/ipmr.c:reg_vif_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589459428,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ipmr_base.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589504837,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer",
        "net/xfrm/xfrm_policy.c:xfrm_policy_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589521678,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589611212,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:ip6_forward",
        "net/ipv6/ip6_output.c:ip6_forward"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589682235,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:rt6_score_route"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589728619,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589784668,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/raw.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/raw.c:raw6_icmp_error",
        "net/ipv6/raw.c:raw6_local_deliver"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589809346,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/mcast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:inet6_mc_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589885263,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv6/ip6mr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6mr_get_route",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6_mr_input",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_compat_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:ip6mr_ioctl",
        "net/ipv6/ip6mr.c:reg_vif_xmit",
        "net/ipv6/ip6mr.c:pim6_rcv",
        "net/ipv6/ip6mr.c:ip6mr_vif_seq_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589944401,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590013838,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
  "name": "arch_atomic_add_return",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578871086,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578940392,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_box_unref",
        "arch/x86/events/intel/uncore.c:uncore_pci_remove",
        "arch/x86/events/intel/uncore.c:uncore_pci_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171150,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "arch/x86/kernel/cpu/mce/core.c:mce_panic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179018,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425434,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:mmiotrace_ioremap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579571605,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__sigqueue_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579865989,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_sched_domains",
        "kernel/sched/topology.c:build_overlap_sched_groups"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579876511,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/sched/autogroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/autogroup.c:sched_autogroup_create_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590299237,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/locking/spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/locking/spinlock.c:_raw_read_unlock_irqrestore",
        "kernel/locking/spinlock.c:_raw_read_unlock_irq",
        "kernel/locking/spinlock.c:_raw_read_unlock_bh",
        "kernel/locking/spinlock.c:_raw_read_unlock",
        "kernel/locking/spinlock.c:_raw_read_trylock",
        "kernel/locking/spinlock.c:_raw_read_lock_irqsave",
        "kernel/locking/spinlock.c:_raw_read_lock_irq",
        "kernel/locking/spinlock.c:_raw_read_lock_bh",
        "kernel/locking/spinlock.c:_raw_read_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580006673,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/spurious.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/spurious.c:note_interrupt",
        "kernel/irq/spurious.c:poll_spurious_irqs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580025074,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/irq/irqdomain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/irqdomain.c:__irq_domain_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580057839,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/rcu/tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:sync_rcu_exp_select_node_cpus",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:rcu_implicit_dynticks_qs",
        "kernel/rcu/tree.c:rcu_irq_exit",
        "kernel/rcu/tree.c:rcu_nmi_exit",
        "kernel/rcu/tree.c:rcu_idle_enter",
        "kernel/rcu/tree.c:rcu_dynticks_eqs_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580237269,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:try_release_module_ref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580397551,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/audit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_set_loginuid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580534046,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580619680,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580634046,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/tracing_map.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580638768,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions.c:function_stack_trace_call"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580642520,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_sched_wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_sched_wakeup.c:probe_wakeup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580653487,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_functions_graph.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_functions_graph.c:trace_graph_return",
        "kernel/trace/trace_functions_graph.c:trace_graph_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674914,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable",
        "kernel/trace/trace_events.c:__ftrace_event_enable_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580708400,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580823509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580910765,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064298,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_callchain_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084560,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:padata_do_parallel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138099,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:exit_oom_victim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550117,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_pool_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674483,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:put_page_bootmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782998,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581841452,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004955,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:get_next_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206581,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/notify/notification.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/notification.c:fsnotify_get_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582300509,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431222,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/coredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/coredump.c:do_coredump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582478911,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_send_warning"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582496267,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/proc/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/inode.c:proc_entry_rundown",
        "fs/proc/inode.c:unuse_pde"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582572410,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582607973,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_new_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583019626,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/jbd2/transaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/transaction.c:jbd2_journal_extend",
        "fs/jbd2/transaction.c:add_transaction_credits",
        "fs/jbd2/transaction.c:add_transaction_credits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583167125,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_get_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457017,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/selinux/avc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/selinux/avc.c:avc_alloc_node",
        "security/selinux/avc.c:avc_alloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749631,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584028661,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584208927,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-iocost.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-iocost.c:iocg_kick_delay"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584248485,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_rqw_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584522183,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "lib/sbitmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:__sbq_wake_up"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584681954,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_disable_device",
        "drivers/pci/pci.c:pci_enable_device_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585471349,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_estatus_cache_add",
        "drivers/acpi/apei/ghes.c:__ghes_print_estatus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585710875,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/regulator/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/regulator/core.c:regulator_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725055,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/reset/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585771161,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/tty_buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_buffer.c:tty_buffer_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585871955,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/tty/serial/serial_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586322007,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586414150,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/base/devcoredump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/devcoredump.c:dev_coredumpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586422258,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586522810,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/mfd/mfd-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mfd/mfd-core.c:mfd_cell_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586723399,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586769522,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_release",
        "drivers/scsi/sd.c:sd_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586811063,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_remove_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586853566,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_host_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874225,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/ata/libata-scsi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587634123,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/serio/serio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/serio/serio.c:__serio_register_port"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587657030,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:input_allocate_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826597,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/power/supply/power_supply_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_core.c:power_supply_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588005525,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_next_uevent_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588062261,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_device.c:edac_device_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588070309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci.c:edac_pci_alloc_index"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588073061,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/edac/edac_pci_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588309308,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_boot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588325704,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588332175,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/devfreq/devfreq-event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588339140,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "drivers/extcon/extcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/extcon/extcon.c:extcon_dev_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588391973,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "arch/x86/pci/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/common.c:pcibios_release_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588467220,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/skbuff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:sock_zerocopy_alloc",
        "net/core/skbuff.c:skb_release_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588536289,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netstamp_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588624170,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/dst.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dst.c:dst_release_immediate",
        "net/core/dst.c:dst_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588648197,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:___neigh_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588781755,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/page_pool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/page_pool.c:__page_pool_clean_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588799334,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/netpoll.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/netpoll.c:netpoll_send_udp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588859343,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/sock_map.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_update_common"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588925309,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589020987,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_release",
        "net/netlink/af_netlink.c:netlink_skb_destructor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589080324,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/ip_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_fragment.c:ip_frag_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589315640,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp_enqueue_schedule_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589568782,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:xfrm_get_acqseq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589996689,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590063918,
      "name": "arch_atomic_add_return",
      "external": false,
      "loc": "arch/x86/include/asm/atomic.h:165",
      "file": "net/rfkill/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/rfkill/core.c:rfkill_fop_ioctl",
        "net/rfkill/core.c:rfkill_fop_release"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int arch_atomic_add_return(int i, atomic_t * v)
```
</details>
</li>
</ul>
