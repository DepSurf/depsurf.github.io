# Function: <code>static_key_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "static_key_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595004174,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:217",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579527879,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:217",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_feat_write",
        "kernel/sched/core.c:sysctl_numa_balancing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579976513,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:217",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:rebind_subsystems"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580538304,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:81",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/kernel/tsc.c:tsc_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/events/core.c:perf_event_alloc",
        "lib/dynamic_debug.c:ddebug_exec_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580538304,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580602336,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:81",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602336,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580632208,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:82",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632208,
      "name": "static_key_enable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580713488,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:151",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/hmm.c:hmm_devmem_add",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580713488,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845584,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:152",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/debug.c:sched_feat_write",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/memremap.c:dev_pagemap_get_ops",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear",
        "net/ipv4/udp.c:udp_lib_setsockopt",
        "net/ipv6/udp.c:udpv6_encap_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845584,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914384,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:172",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/memremap.c:dev_pagemap_get_ops",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/usercopy.c:set_hardened_usercopy",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914384,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012560,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:devm_memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012560,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069056,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069056,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248848,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:account_event",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248848,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290816,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/sev-es.c:sev_es_init_vc_handling",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:account_event",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/shuffle.c:shuffle_store",
        "mm/slub.c:setup_slub_debug",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290816,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581308480,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:account_event",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/shuffle.c:shuffle_store",
        "mm/slub.c:setup_slub_debug",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308480,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553408,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/irq/manage.c:setup_forced_irqthreads",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:account_event",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/shuffle.c:shuffle_store",
        "mm/slub.c:setup_slub_debug",
        "mm/kfence/core.c:kfence_init",
        "mm/memcontrol.c:memcg_online_kmem",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "net/core/dev.c:netstamp_clear",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553408,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581905088,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__set_sched_clock_stable",
        "kernel/sched/build_utility.c:housekeeping_init",
        "kernel/irq/manage.c:setup_forced_irqthreads",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/events/core.c:account_event",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/shuffle.c:shuffle_store",
        "mm/slub.c:setup_slub_debug",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "crypto/algapi.c:crypto_algapi_init",
        "lib/dynamic_debug.c:ddebug_change",
        "lib/vsprintf.c:enable_ptr_key_workfn",
        "drivers/char/random.c:random_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905088,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582339344,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:215",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_enable",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__set_sched_clock_stable",
        "kernel/sched/build_utility.c:housekeeping_init",
        "kernel/irq/manage.c:setup_forced_irqthreads",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/events/core.c:account_event",
        "mm/vmscan.c:store_enabled",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/page_alloc.c:init_mem_debugging_and_hardening",
        "mm/shuffle.c:shuffle_param_set",
        "mm/slub.c:setup_slub_debug",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/char/random.c:random_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target",
        "net/sched/sch_api.c:pktsched_init",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582339344,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541312,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:215",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:taa_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__set_sched_clock_stable",
        "kernel/sched/build_utility.c:housekeeping_init",
        "kernel/irq/manage.c:setup_forced_irqthreads",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/events/core.c:account_event",
        "mm/vmscan.c:enabled_store",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/shuffle.c:shuffle_param_set",
        "mm/slub.c:setup_slub_debug",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/char/random.c:random_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target",
        "net/sched/sch_api.c:pktsched_init",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541312,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710464,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:215",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:early_randomize_kstack_offset",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/fpu/xstate.c:xfd_update_static_branch",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "arch/x86/crypto/blake2s-glue.c:blake2s_mod_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:__sched_setscheduler",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:setup_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/core.c:set_numabalancing_state",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sysctl_sched_uclamp_handler",
        "kernel/sched/core.c:sched_core_get",
        "kernel/sched/build_utility.c:psi_init",
        "kernel/sched/build_utility.c:__set_sched_clock_stable",
        "kernel/sched/build_utility.c:housekeeping_init",
        "kernel/irq/manage.c:setup_forced_irqthreads",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_migration_handler",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/delayacct.c:sysctl_delayacct",
        "kernel/delayacct.c:delayacct_init",
        "kernel/tracepoint.c:tracepoint_add_func",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/trace/fgraph.c:ftrace_return_to_handler",
        "kernel/events/core.c:account_event",
        "mm/vmscan.c:enabled_store",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/mm_init.c:mm_core_init",
        "mm/slab_common.c:kmem_cache_create_usercopy",
        "mm/shuffle.c:shuffle_param_set",
        "mm/slub.c:setup_slub_debug",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/page_reporting.c:page_reporting_register",
        "lib/dynamic_debug.c:ddebug_change",
        "drivers/char/random.c:random_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init",
        "drivers/gpu/drm/drm_cache.c:drm_memcpy_init_early",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/md/dm-table.c:dm_table_add_target",
        "net/sched/sch_api.c:pktsched_init",
        "net/netfilter/nf_hooks_lwtunnel.c:nf_hooks_lwtunnel_sysctl_handler",
        "net/ipv4/ip_sockglue.c:do_ip_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710464,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492429520,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpufeature.c:enable_cpu_capabilities",
        "arch/arm64/kernel/cpufeature.c:setup_cpu_features",
        "virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init",
        "virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe",
        "virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe",
        "virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "drivers/irqchip/irq-gic-v3.c:gic_init_bases",
        "drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492429520,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224763412,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 3224939240,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:force_schedstat_enabled"
      ]
    },
    {
      "addr": 3243374648,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243375076,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3225320692,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/time/timer.c:timers_update_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 3225520616,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": []
    },
    {
      "addr": 3225813120,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 3226235004,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:account_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3226685712,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc"
      ]
    },
    {
      "addr": 3244024088,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 3243464072,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:set_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "drivers/irqchip/irq-gic-v3.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235385356,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224907516,
      "name": "static_key_enable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 3225804412,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 3226685712,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285697776,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/setup.c:pSeries_setup_arch",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285697776,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271427538,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:proc_do_static_key"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271558602,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:sysctl_schedstats"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:force_schedstat_enabled"
      ]
    },
    {
      "addr": 18446743936270627926,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/isolation.c:housekeeping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270628238,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/sched/psi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/psi.c:psi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271827892,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/time/timer.c:timers_update_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271970536,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:rebind_subsystems"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272164852,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/trace/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/trace/trace.c:tracepoint_printk_sysctl"
      ],
      "caller_func": [
        "kernel/trace/trace.c:early_trace_init"
      ]
    },
    {
      "addr": 18446743936272475622,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272826974,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc"
      ]
    },
    {
      "addr": 18446743936270890346,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/shuffle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shuffle.c:page_alloc_shuffle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270704868,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "mm/usercopy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/usercopy.c:set_hardened_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278819772,
      "name": "static_key_enable",
      "external": false,
      "loc": "include/linux/jump_label.h:304",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271540532,
      "name": "static_key_enable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446743936272157606,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446743936272826974,
      "name": "static_key_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037904,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037904,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580983984,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983984,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029104,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029104,
      "name": "static_key_enable",
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
void static_key_enable(struct static_key * key)
```

```json
{
  "name": "static_key_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090528,
      "name": "static_key_enable",
      "external": true,
      "loc": "kernel/jump_label.c:187",
      "file": "kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw",
        "arch/x86/xen/mmu_pv.c:xen_after_bootmem",
        "arch/x86/kernel/tsc.c:tsc_enable_sched_clock",
        "arch/x86/kernel/cpu/common.c:identify_boot_cpu",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:cpu_bugs_smt_update",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:mds_select_mitigation",
        "arch/x86/kernel/apic/ipi.c:apic_smt_update",
        "arch/x86/mm/mem_encrypt.c:mem_encrypt_init",
        "kernel/sysctl.c:proc_do_static_key",
        "kernel/sched/core.c:sched_init",
        "kernel/sched/core.c:sysctl_schedstats",
        "kernel/sched/core.c:force_schedstat_enabled",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/clock.c:sched_clock_init_late",
        "kernel/sched/isolation.c:housekeeping_init",
        "kernel/sched/psi.c:psi_init",
        "kernel/time/timer.c:timer_update_keys",
        "kernel/time/timer.c:timers_update_migration",
        "kernel/cgroup/cgroup.c:rebind_subsystems",
        "kernel/trace/trace.c:early_trace_init",
        "kernel/trace/trace.c:register_ftrace_export",
        "kernel/trace/trace.c:tracepoint_printk_sysctl",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmstat.c:sysctl_vm_numa_stat_handler",
        "mm/page_alloc.c:early_init_on_free",
        "mm/page_alloc.c:early_init_on_alloc",
        "mm/shuffle.c:page_alloc_shuffle",
        "mm/usercopy.c:set_hardened_usercopy",
        "mm/memremap.c:memremap_pages",
        "lib/dynamic_debug.c:ddebug_exec_query",
        "net/core/dev.c:netstamp_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090528,
      "name": "static_key_enable",
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
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void static_key_enable(struct static_key * key)
```
</details>
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
