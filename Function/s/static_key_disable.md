# Function: <code>static_key_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579527950,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:227",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sysctl_numa_balancing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579971840,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:227",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971840,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538624,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:92",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/events/core.c:perf_sched_delayed",
        "lib/dynamic_debug.c:ddebug_exec_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538624,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602656,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:92",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:cgroup_init",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602656,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632496,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:93",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_kill_sb",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632496,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713664,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:175",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713664,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845776,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:176",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "kernel/memremap.c:dev_pagemap_put_ops",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845776,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914576,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:197",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_lock_cpu",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "kernel/memremap.c:dev_pagemap_put_ops",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914576,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012752,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012752,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069248,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069248,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249040,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/vsprintf.c:initialize_ptr_random",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249040,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581291008,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/tracepoint.c:tracepoint_remove_func",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/vsprintf.c:initialize_ptr_random",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581291008,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308672,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/vsprintf.c:initialize_ptr_random",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308672,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553616,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/smpboot.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/slub.c:setup_slub_debug",
        "lib/once.c:once_deferred",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/vsprintf.c:initialize_ptr_random",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553616,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905312,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/slub.c:setup_slub_debug",
        "lib/once.c:once_deferred",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/dynamic_debug.c:ddebug_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905312,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339600,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:240",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmscan.c:store_enabled",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/slub.c:setup_slub_debug",
        "lib/once.c:once_deferred",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/dynamic_debug.c:ddebug_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339600,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541568,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:240",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmscan.c:enabled_store",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/slub.c:setup_slub_debug",
        "lib/once.c:once_deferred",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/dynamic_debug.c:ddebug_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541568,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710720,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:240",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__sched_clock_work",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:cgroup_disable",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_probe_unregister",
        "kernel/trace/trace.c:late_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmscan.c:enabled_store",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/slub.c:setup_slub_debug",
        "lib/once.c:once_deferred",
        "lib/crc-t10dif.c:crc_t10dif_rehash",
        "lib/crc64-rocksoft.c:crc64_rocksoft_rehash",
        "lib/dynamic_debug.c:ddebug_change"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710720,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492430096,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/irqchip/irq-gic.c:gic_v2_acpi_init",
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_init",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492430096,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224763572,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3224939388,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sysctl_schedstats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    },
    {
      "addr": 3225320340,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_update_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 3225520416,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init"
      ]
    },
    {
      "addr": 3225806948,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3226224916,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_sched_delayed"
      ],
      "caller_func": []
    },
    {
      "addr": 3226685884,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc"
      ]
    },
    {
      "addr": 3244023908,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 3229471600,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229703956,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "drivers/irqchip/irq-gic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic.c:gic_of_init",
        "drivers/irqchip/irq-gic.c:gic_init"
      ]
    },
    {
      "addr": 3243554728,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases"
      ],
      "caller_func": []
    },
    {
      "addr": 3236516360,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229703956,
      "name": "static_key_disable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 3224907328,
      "name": "static_key_disable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3225498096,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 3226685884,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 3236516360,
      "name": "static_key_disable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285698368,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/cputable.c:mmu_feature_keys_init",
        "arch/powerpc/kernel/cputable.c:cpu_feature_keys_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/once.c:once_deferred",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285698368,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271427694,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271558726,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sysctl_schedstats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init"
      ]
    },
    {
      "addr": 18446743936271827686,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timers_update_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271970362,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_init"
      ]
    },
    {
      "addr": 18446743936272160094,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272459094,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_sched_delayed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272827058,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc"
      ]
    },
    {
      "addr": 18446743936270890252,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275204468,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "lib/once.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279779032,
      "name": "static_key_disable",
      "external": false,
      "loc": "include/linux/jump_label.h:315",
      "file": "lib/vsprintf.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271540426,
      "name": "static_key_disable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446743936271949928,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446743936272827058,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446743936279779032,
      "name": "static_key_disable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581038096,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038096,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984176,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984176,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029296,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029296,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void static_key_disable(struct static_key * key)
```

```json
{
  "name": "static_key_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090720,
      "name": "static_key_disable",
      "external": true,
      "loc": "kernel/jump_label.c:212",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/spinlock.c:xen_init_spinlocks",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/paravirt.c:native_pv_lock_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:__sched_clock_work",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:unregister_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_sched_delayed",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/memremap.c:devmap_managed_enable_put",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "lib/vsprintf.c:initialize_ptr_random"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090720,
      "name": "static_key_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
